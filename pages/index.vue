<template>
  <div class="w-full h-screen flex items-center justify-center">
    <div class="text-center">
      <h1 class="text-4xl font-bold">Welcome to BlueScript Poster.</h1>
      <p class="text-lg mt-4">Click on button below to see the pages!</p>
      <div class="flex justify-center mt-8 space-x-2">
        <UButton to="/p1" trailing icon="i-ph-arrow-right">Page 1</UButton>
        <UButton to="/p2" trailing icon="i-ph-arrow-right">Page 2</UButton>
        <UColorModeButton />
      </div>
    </div>
  </div>
</template>
