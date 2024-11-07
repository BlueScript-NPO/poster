<template>
  <div class="w-full h-screen bg-white text-zinc-950 break-keep">
    <ScalingPoster>
      <div
        class="p-6 w-full h-full bg-white grid grid-cols-12 grid-rows-6 gap-4"
      >
        <!-- Box 1: Top Left Small Box -->
        <div class="col-span-3 row-span-2 col-start-10 row-start-5">
          <BentoCard
            class="bg-gradient-to-b from-zinc-50 to-zinc-100 text-zinc-700"
          >
            <div class="w-full flex justify-center pb-4">
              <h1 class="text-3xl font-normal">
                First <span class="font-semibold">Steps</span>
              </h1>
            </div>

            <div class="flex-col space-y-4 px-2 pb-6">
              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">4</span>
                Expert Advisors
              </p>
              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">6</span>
                Partner Institutions
              </p>
              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">14</span>
                Development Contributors
              </p>
              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">13k</span>
                MAU
              </p>
            </div>

            <p class="text-lg px-2">
              BlueScript is a living software, continuously evolving to meet
              users’ needs.
            </p>
          </BentoCard>
        </div>

        <!-- Box 2: Top Center Medium Box -->
        <div class="col-span-3 row-span-1 col-start-10 row-start-4">
          <BentoCard>
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Development Plans</span>
              </h1>
            </div>

            <div class="flex-col space-y-2 text-lg">
              <p>Visual Training Module</p>
              <p>Auditory Training Module</p>
              <p>Enhanced Online Service</p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 3: Bottom Wide Box -->
        <div class="col-span-9 row-span-1 col-start-1 row-start-6">
          <BentoCard
            class="border-none bg-gradient-to-b from-zinc-800 to-black text-white"
          >
            <div class="w-full flex justify-center pb-2">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Revolutionize</span> the
                <span class="font-semibold">Landscape</span>
              </h1>
            </div>

            <div class="flex w-full justify-between text-lg">
              <div class="w-98">
                <p>
                  Millions of children worldwide struggling with dyslexia
                  shouldn’t suffer the same challenges.
                  <span class="text-3xl font-semibold text-negative">
                    Thousands
                  </span>
                  should find relief, as I did.
                </p>
              </div>
              <div class="space-y-2">
                <p>
                  BlueScript represents not just a tool, but the
                  <span class="text-3xl font-semibold text-gold"
                    >collective effort of everyone</span
                  >
                  to overcome dyslexia.
                </p>
                <p>
                  Public
                  <span class="text-3xl font-semibold text-gold"
                    >engagement</span
                  >
                  is essential for promoting dyslexia treatment.
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 4: Large Center Box -->
        <div class="col-span-9 row-span-2 col-start-1 row-start-4">
          <BentoCard>
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Training Modules</span>
              </h1>
            </div>

            <div class="flex flex-wrap gap-4 justify-between pt-4 px-12">
              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Rapid Visual Perception.png" />
                <p class="text-xl font-semibold">Rapid Visual Perception</p>
                <p class="text-xs">
                  Identifying characters appearing on screen in under 250ms.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Sequential Visual Memory.png" />
                <p class="text-xl font-semibold">Sequential Visual Memory</p>
                <p class="text-xs">
                  Identifying and memorizing a series of characters, then
                  recalling them.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Sequencing.png" />
                <p class="text-xl font-semibold">Character Sequencing</p>
                <p class="text-xs">
                  Finding sequences and entering characters with arrows and
                  spacebar.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Matching.png" />
                <p class="text-xl font-semibold">Character Matching</p>
                <p class="text-xs">
                  Clicking matching characters among similar-looking strings.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Guesstimate.png" />
                <p class="text-xl font-semibold">Character Guesstimate</p>
                <p class="text-xs">
                  Quickly identifying characters as they gradually appear.
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 5: Bottom Left Medium Box -->
        <div class="col-span-6 row-span-2 col-start-1 row-start-1">
          <BentoCard>
            <div class="w-full flex justify-center mb-8">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Infrastructure</span>
              </h1>
            </div>

            <NuxtImg src="/Infrastructure.png" class="p-4" />

            <div class="text-lg mt-8">
              <p>
                Deployed as
                <span class="text-5xl font-semibold">Docker</span> based
                <span class="text-5xl font-semibold">SaaS</span> for easy
                distribution.
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 6: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-1 col-start-1 row-start-3">
          <BentoCard
            class="bg-gradient-to-b from-zinc-50 to-zinc-100 text-zinc-700"
          >
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">With the Community</span>
              </h1>
            </div>

            <div class="flex justify-between w-full">
              <div class="flex flex-col space-y-3">
                <p class="text-xl">
                  Development Collaboration on GitHub <br />
                  <span class="text-3xl font-semibold text-gold-light"
                    >Open to All</span
                  >
                </p>
                <p class="text-xl">
                  Community Translations on Crowdin <br />
                  <span class="font-semibold text-gold-light">9 Languages</span>
                  <span class="text-3xl font-semibold text-gold-light"
                    >Shared Worldwide</span
                  >
                </p>
              </div>
              <div class="grid grid-col gap-4 text-right text-lg">
                <p>
                  7M Instagram Views <br />
                  <span class="font-semibold text-3xl text-gold-light"
                    >Engagement with Experts</span
                  >
                  <br />
                  <span class="text-sm"
                    >Special Ed. Teachers & Dyslexia Experts</span
                  >
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 7: Bottom Right Medium Box -->
        <div class="col-span-6 row-span-3 col-start-7 row-start-1">
          <BentoCard>
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">Architecture</span>
              </h1>
            </div>

            <NuxtImg src="/architecture.png" class="p-4" />

            <div class="text-lg mb-4">
              <p class="text-center">
                <span class="text-5xl font-semibold">PWA</span> Frontend and
                Backend structure
              </p>
            </div>

            <table>
              <tr>
                <td class="px-4 font-semibold w-28">Frontend</td>
                <td class="px-4">
                  Server Side Rendering with Nuxt.js, TailwindCSS, NuxtUI.
                </td>
              </tr>
              <tr>
                <td class="px-4 py-2 font-semibold">Backend</td>
                <td class="px-4 py-2">
                  Built on
                  <span class="font-semibold">Python FastAPI</span> framework.
                </td>
              </tr>
            </table>
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
