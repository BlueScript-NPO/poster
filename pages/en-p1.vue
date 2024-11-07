<template>
  <div class="w-full h-screen bg-white text-zinc-950 break-keep">
    <ScalingPoster>
      <div
        class="p-6 w-full h-full bg-white grid grid-cols-12 grid-rows-6 gap-4"
      >
        <!-- Box 1: Top Left Small Box -->
        <div class="col-span-3 row-span-2 col-start-7 row-start-3">
          <BentoCard
            class="border-none bg-gradient-to-b from-zinc-950 to-black text-white"
          >
            <div class="w-full flex justify-center mb-4">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">My</span> Dyslexia
              </h1>
            </div>

            <p class="italic pb-2 text-xl text-right mb-4">
              I'm still battling with <br />
              dyslexia.
            </p>

            <p class="pb-2 text-lg">
              <span class="text-5xl font-semibold text-negative">Dyslexia</span>
              Learning difficulty in reading comprehension, not reading itself.
            </p>

            <p class="pb-2 text-lg">
              After
              <span class="text-5xl font-semibold text-negative">2 years</span>
              of intense training in middle school, partial recovery achieved.
            </p>
            <p class="text-lg">
              Yet,
              <span class="font-semibold text-negative">late timing</span>
              prevented full recovery.
            </p>
          </BentoCard>
        </div>

        <!-- Box 2: Top Center Medium Box -->
        <div class="col-span-6 row-span-1 col-start-7 row-start-1">
          <BentoCard
            class="border-none bg-gradient-to-b from-zinc-800 to-black text-white"
          >
            <div class="w-full flex justify-center pb-8">
              <h1 class="text-3xl font-normal">
                Dyslexia <span class="font-semibold">in Numbers</span>
              </h1>
            </div>

            <div class="flex justify-between w-full">
              <div class="flex flex-col space-y-3">
                <p class="text-xl">
                  About
                  <span class="text-3xl font-semibold text-negative">5%</span>
                  of the world population
                </p>
                <p class="text-xl">
                  Golden Time:
                  <span class="text-3xl font-semibold text-negative">12y</span>
                </p>
              </div>
              <div class="grid gap-4 text-right text-lg">
                <p>
                  Insurance
                  <span class="font-semibold text-negative">Gaps</span>
                </p>
                <p>
                  Costly
                  <span class="font-semibold text-negative">Training Fees</span>
                </p>
                <p>
                  Lack of
                  <span class="font-semibold text-negative">localized</span>
                  solutions from overseas companies
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 3: Top Right Small Box -->
        <div class="col-span-3 row-span-3 col-start-10 row-start-4">
          <BentoCard
            class="bg-gradient-to-b from-zinc-50 to-zinc-100 text-zinc-700"
          >
            <div class="w-full flex justify-center pb-12">
              <h1 class="text-3xl font-normal">
                The <span class="font-semibold">Potential</span> of
                <span class="font-semibold">Inspiration</span>
              </h1>
            </div>

            <div class="text-lg space-y-4">
              <p>
                <span class="text-5xl font-semibold text-gold-light">1.</span>
                Dyslexia training accessible to anyone with a computer.
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light">2.</span>
                Open access to code for modification and sharing.
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light">3.</span>
                Community-driven program development.
              </p>
            </div>

            <div class="w-full flex py-6 justify-center">
              <icon name="i-ph-arrow-down" class="text-2xl" />
            </div>

            <div class="space-y-4">
              <p>
                <span class="text-5xl font-semibold text-gold-light"
                  >Web App</span
                >
                allows easy training anywhere.
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light"
                  >Open Source</span
                >
                Model
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 4: Large Center Box -->
        <div class="col-span-6 row-span-4 col-start-1 row-start-1">
          <BentoCard
            class="relative bg-blueScriptBlue-800 text-white border-none"
          >
            <div class="absolute inset-0">
              <NuxtImg src="/mockup-1.png" class="w-full h-full object-cover" />
            </div>

            <div
              class="relative z-10 w-full flex justify-center items-center h-[30%] flex-col text-center p-4"
            >
              <NuxtImg src="/logo-dark.svg" class="w-[23%]" />
              <p class="mt-4 font-normal text-3xl mb-6">
                Training program based on
                <span class="text-6xl font-semibold">Neuroscience </span>
                Methodology for Dyslexia
              </p>
              <p class="text-2xl">Coding Scholar, SuhJae</p>

              <p class="italic text-sm">The developer of morning calm.</p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 5: Middle Left Tall Box -->
        <div class="col-span-3 row-span-2 col-start-10 row-start-2">
          <BentoCard>
            <div class="w-full flex justify-center pb-16">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Source</span> of
                <span class="font-semibold">Inspiration</span>
              </h1>
            </div>

            <div>
              <p class="text-left text-lg">
                <span class="font-semibold">Software distribution</span> costs
                can approach <span class="text-3xl font-semibold">zero</span>,
                yet it can greatly impact lives.
              </p>
            </div>

            <div class="w-full flex py-6 justify-center">
              <icon name="i-ph-x" class="text-2xl" />
            </div>

            <div>
              <p class="text-left text-lg">
                Is there help available for
                <span class="font-semibold text-3xl"> dylexic </span>
                in South Korea?
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 6: Middle Right Tall Box -->
        <div class="col-span-3 row-span-2 col-start-1 row-start-5">
          <BentoCard class="px-6">
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Neuroplasticity</span>
              </h1>
            </div>
            <p class="italic text-zinc-700 text-md text-right pb-20">
              (Synaptic Plasticity)
            </p>

            <div>
              <p class="text-left text-lg">
                Using intense, repetitive
                <span class="text-3xl font-semibold">stimulation</span>
                to form neural circuits that improve reading information flow.
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 7: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-2 col-start-4 row-start-5">
          <BentoCard>
            <div class="w-full flex justify-center pb-14">
              <h1 class="text-3xl font-semibold">A New Perspective</h1>
            </div>

            <div class="text-lg text-center">
              <p>
                Approaching dyslexia from a
                <span class="text-5xl font-semibold">Neuroscientific</span>
                rather than linguistic perspective.
              </p>
              <p>
                Dyslexia involves inefficient neural circuits for reading areas.
              </p>
            </div>

            <div class="w-full flex py-6 pt-8 justify-center">
              <icon name="i-ph-arrow-down" class="text-2xl" />
            </div>

            <div class="text-lg space-y-4 text-center">
              <p>
                Using
                <span class="text-5xl font-semibold">Neuroplasticity</span> to
                restructure inefficient circuits
                <span class="text-5xl font-semibold">efficiently</span>.
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 8: Bottom Wide Box -->
        <div class="col-span-3 row-span-1 col-start-7 row-start-2">
          <BentoCard>
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Learn More</span>
              </h1>
            </div>

            <div class="flex flex-col space-y-2">
              <div class="flex space-x-1">
                <Icon name="i-mdi-github" class="text-xl" />
                <p class="text-sm">github.com/blueScript-NPO</p>
              </div>
              <div class="flex space-x-1">
                <Icon name="i-ph-globe" class="text-xl" />
                <p class="text-sm">bluescript.app</p>
              </div>
            </div>

            <div class="flex px-6 pt-3">
              <NuxtImg src="/qr/github.gif" class="w-1/2" />
              <NuxtImg src="/qr/bluescript.gif" class="w-1/2" />
            </div>
          </BentoCard>
        </div>
      </div>
    </ScalingPoster>
  </div>
</template>

<style scoped>
.text-gold {
  background: linear-gradient(to bottom, #c7b499 27%, #d9c5a9 40%, #d3c6b4 78%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.text-gold-light {
  background: linear-gradient(to bottom, #c7b499 27%, #d3c6b4 40%, #b2a391 78%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}

.text-negative {
  background: linear-gradient(to bottom, #d0828b 27%, #bd7e83 40%, #994e60 78%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
}
</style>
