<template>
  <div class="w-full h-screen bg-zinc-950">
    <ScalingPoster>
      <div
        class="p-8 w-full h-full bg-white grid grid-cols-12 grid-rows-6 gap-6"
      >
        <!-- Box 1: Top Left Small Box -->
        <div
          class="col-span-3 row-span-2 col-start-1 row-start-1 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 1</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 2: Top Center Medium Box -->
        <div
          class="col-span-6 row-span-1 col-start-4 row-start-1 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 2</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 3: Top Right Small Box -->
        <div
          class="col-span-3 row-span-2 col-start-10 row-start-1 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 3</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 4: Large Center Box -->
        <div
          class="col-span-6 row-span-3 col-start-4 row-start-2 border border-gray-300 rounded-lg p-6 flex flex-col justify-center items-center shadow-xl bg-white"
        >
          <div class="poster-content text-2xl font-bold">Box 4 (Featured)</div>
          <UButton class="mt-4">Discover More</UButton>
        </div>

        <!-- Box 5: Middle Left Tall Box -->
        <div
          class="col-span-3 row-span-3 col-start-1 row-start-3 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 5</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 6: Middle Right Tall Box -->
        <div
          class="col-span-3 row-span-3 col-start-10 row-start-3 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 6</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 7: Bottom Center Medium Box -->
        <div
          class="col-span-6 row-span-1 col-start-4 row-start-5 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-lg bg-white"
        >
          <div class="poster-content">Box 7</div>
          <UButton>Click Me</UButton>
        </div>

        <!-- Box 8: Bottom Wide Box -->
        <div
          class="col-span-12 row-span-1 col-start-1 row-start-6 border border-gray-300 rounded-lg p-4 flex flex-col justify-center items-center shadow-md bg-white"
        >
          <div class="poster-content">Box 8</div>
          <UButton>Click Me</UButton>
        </div>
      </div>
    </ScalingPoster>
  </div>
</template>
