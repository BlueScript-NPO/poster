<template>
  <div class="w-full h-screen bg-zinc-950 text-zinc-950 break-keep">
    <ScalingPoster>
      <div
        class="p-8 w-full h-full bg-white grid grid-cols-12 grid-rows-6 gap-4"
      >
        <!-- Box 1: Top Left Small Box -->
        <div class="col-span-3 row-span-2 col-start-1 row-start-1">
          <BentoCard>
            <div class="poster-content">Box 1</div>
          </BentoCard>
        </div>

        <!-- Box 2: Top Center Medium Box -->
        <div class="col-span-6 row-span-1 col-start-4 row-start-1">
          <BentoCard>
            <div class="poster-content">Box 2</div>
          </BentoCard>
        </div>

        <!-- Box 3: Top Right Small Box -->
        <div class="col-span-3 row-span-3 col-start-10 row-start-1">
          <BentoCard>
            <div class="poster-content">Box 3</div>
          </BentoCard>
        </div>

        <!-- Box 4: Large Center Box -->
        <div class="col-span-6 row-span-2 col-start-4 row-start-2">
          <BentoCard>
            <div class="poster-content text-2xl font-bold">
              Box 4 (Featured)
            </div>
          </BentoCard>
        </div>

        <!-- Box 5: Middle Left Tall Box -->
        <div class="col-span-3 row-span-2 col-start-1 row-start-3">
          <BentoCard>
            <div class="poster-content">Box 5</div>
          </BentoCard>
        </div>

        <!-- Box 6: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-2 col-start-1 row-start-5">
          <BentoCard>
            <div class="w-full flex justify-center pb-16">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold"> 인프라스트럭처 </span>
              </h1>
            </div>

            <NuxtImg src="/Infrastructure.png" />
          </BentoCard>
        </div>

        <!-- Box 7: Bottom Center Medium Box -->
        <div class="col-span-3 row-span-1 col-start-4 row-start-4">
          <BentoCard>
            <div class="poster-content">Box 7</div>
          </BentoCard>
        </div>

        <!-- Box 8: Bottom Wide Box -->
        <div class="col-span-6 row-span-3 col-start-7 row-start-4">
          <BentoCard>
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold"> 아키텍처 </span>
              </h1>
            </div>

            <div class="text-lg">
              <p>
                <span class="text-5xl font-semibold">PWA</span>
                프런트엔드 및 백엔드로 구성
              </p>
              <p>
                배포 용이성을 위해
                <span class="text-5xl font-semibold">Docker</span> 기반
                <span class="text-5xl font-semibold">SaaS</span>
                구성
              </p>
            </div>

            <NuxtImg src="/architecture.png" class="px-10 py-6" />

            <tbody>
              <tr>
                <td class="px-4 font-semibold w-28">프런트엔드</td>
                <td class="px-4">
                  Nuxt.js, TailwindCSS, NuxtUI 프레임워크 등을 활용한 Server
                  Side Rendering 지원
                </td>
              </tr>
              <tr>
                <td class="px-4 py-2 font-semibold">백엔드</td>
                <td class="px-4 py-2">Python FastAPI 프레임워크 활용</td>
              </tr>
            </tbody>
          </BentoCard>
        </div>
      </div>
    </ScalingPoster>
  </div>
</template>
