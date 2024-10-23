<template>
  <div class="scaling-poster-container">
    <div ref="scalingContainer" class="scaling-container">
      <div ref="posterWrapper" class="poster-wrapper">
        <!-- Use slot to include poster content -->
        <slot />
      </div>
    </div>
  </div>
</template>

<script setup>
import { ref, onMounted, onBeforeUnmount, nextTick } from "vue";

const scalingContainer = ref(null);
const posterWrapper = ref(null);

// A0 size in mm
const posterWidthMm = 841;
const posterHeightMm = 1189;

const calculateScale = () => {
  if (scalingContainer.value && posterWrapper.value) {
    const parentWidth = scalingContainer.value.clientWidth;
    const parentHeight = scalingContainer.value.clientHeight;

    // Get the poster size in pixels
    const posterWidthPx = posterWrapper.value.offsetWidth;
    const posterHeightPx = posterWrapper.value.offsetHeight;

    const widthScale = parentWidth / posterWidthPx;
    const heightScale = parentHeight / posterHeightPx;

    const scale = Math.min(widthScale, heightScale);

    posterWrapper.value.style.transform = `scale(${scale})`;
    posterWrapper.value.style.transformOrigin = "top left";
  }
};

onMounted(() => {
  nextTick(() => {
    calculateScale();
    window.addEventListener("resize", calculateScale);
  });
});

onBeforeUnmount(() => {
  window.removeEventListener("resize", calculateScale);
});
</script>

<style scoped>
.scaling-poster-container {
  width: 100%;
  height: 100vh;
  position: absolute;
  overflow: hidden;
}

.scaling-container {
  width: 100%;
  height: 100%;
  position: absolute;
  overflow: auto;
}

.poster-wrapper {
  width: 297mm;
  height: 420mm;
  background-color: white;
  position: absolute;
}

@media print {
  .scaling-poster-container,
  .scaling-container {
    width: auto;
    height: auto;
    overflow: visible;
  }

  .poster-wrapper {
    transform: none !important;
    transform-origin: top left !important;
    width: 297mm !important;
    height: 420mm !important;
  }
}
</style>
