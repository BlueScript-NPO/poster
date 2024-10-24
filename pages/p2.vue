<template>
  <div class="w-full h-screen white text-zinc-950 break-keep">
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
                첫 <span class="font-semibold">걸음</span>
              </h1>
            </div>

            <div class="flex-col space-y-4 px-2 pb-8">
              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">4</span>
                전문 자문가
              </p>

              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">6</span>

                공식 제휴 기관
              </p>

              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">14</span>

                개발 기여자
              </p>

              <p class="text-xl">
                <span class="text-5xl font-semibold text-gold-light">13k</span>
                월간 사용자
              </p>
            </div>

            <p class="text-lg">
              BlueScript는 완성된 소프트웨어가 아닌 사용자들에 맞추어 계속
              변하는 살아있는 소프트웨어 입니다.
            </p>
          </BentoCard>
        </div>

        <div class="col-span-3 row-span-1 col-start-10 row-start-4">
          <BentoCard>
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">발전 계획</span>
              </h1>
            </div>

            <div class="flex-col space-y-2 text-lg">
              <p>시각 훈련 모듈</p>
              <p>청각 훈련 모듈</p>
              <p>온라인 서비스 강화</p>
              <p>훈련 결과 추적 및 분석 기능</p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 2: Top Center Medium Box -->
        <div class="col-span-9 row-span-1 col-start-1 row-start-6">
          <BentoCard
            class="border-none bg-gradient-to-b from-zinc-800 to-black text-white"
          >
            <div class="w-full flex justify-center pb-2">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">판도</span>를
                <span class="font-semibold"> 뒤집다</span>
              </h1>
            </div>

            <div class="flex w-full justify-between text-lg">
              <div class="w-98">
                <p>
                  난독증으로 어려움을 겪고 있는 전세계
                  <span class="text-3xl font-semibold text-negative">
                    수천만명</span
                  >의 아이들이 저처럼
                  <span class="text-3xl font-semibold text-negative"
                    >고통받지 않으면</span
                  >
                  합니다.
                </p>
              </div>
              <div class="space-y-2">
                <p>
                  BlueScript는 단순한 도구가 아니라 난독증 극복을 위한
                  <span class="text-3xl font-semibold text-gold"
                    >모든 사람들의 노력</span
                  >
                  이라 생각합니다.
                </p>
                <p>
                  난독증 치료의 개방과 활성화를 위해서 사람들의
                  <span class="text-3xl font-semibold text-gold"
                    >관심이 필요</span
                  >합니다.
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
                <span class="font-semibold"> 훈련 모듈 </span>
              </h1>
            </div>

            <div class="flex flex-wrap gap-4 justify-between pt-4 px-12">
              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Rapid Visual Perception.png" />
                <p class="text-xl font-semibold">빠른 시각 인지</p>
                <p class="text-sm">
                  250ms 이하의 시간 안에 화면에 나타나는 문자를 식별하고
                  입력하는 훈련.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Sequential Visual Memory.png" />
                <p class="text-xl font-semibold">순차적 시각 기억</p>
                <p class="text-sm">
                  일련의 문자를 순차적으로 식별하고 기억한 후, 일정 시간이 지난
                  후에 다시 입력하는 훈련.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Sequencing.png" />
                <p class="text-xl font-semibold">문자 순차 처리</p>
                <p class="text-sm">
                  보기를 순서대로 찾고, 오른쪽 화살표 키와 스페이스바를 사용하여
                  문자를 입력하는 훈련.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Matching.png" />
                <p class="text-xl font-semibold">문자 대조</p>
                <p class="text-sm">
                  보기와 시각적으로 비슷한 문자열들 중에서 일치하는 문자열을
                  클릭하는 훈련.
                </p>
              </div>

              <div class="flex-col w-[30%] justify-center">
                <NuxtImg src="/Character Guesstimate.png" />
                <p class="text-xl font-semibold">문자 추정</p>
                <p class="text-sm">
                  서서히 나타나는 문자를 가능한 한 빨리 식별하는 훈련.
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 6: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-2 col-start-1 row-start-1">
          <BentoCard>
            <div class="w-full flex justify-center mb-8">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold"> 인프라스트럭처 </span>
              </h1>
            </div>

            <NuxtImg src="/Infrastructure.png" class="p-4" />

            <div class="text-lg mt-8">
              <p>
                배포 용이성을 위해
                <span class="text-5xl font-semibold">Docker</span> 기반
                <span class="text-5xl font-semibold">SaaS</span>
                구성
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 7: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-1 col-start-1 row-start-3">
          <BentoCard
            class="bg-gradient-to-b from-zinc-50 to-zinc-100 text-zinc-700"
          >
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">커뮤니티 </span>와 함께하다
              </h1>
            </div>

            <div class="flex justify-between w-full">
              <div class="flex flex-col space-y-3">
                <p class="text-xl">
                  GitHub를 이용한<br />
                  <span class="text-3xl font-semibold text-gold-light">
                    개발협력</span
                  >
                </p>
                <p class="text-xl">
                  Crowdin을 통한<br />
                  <span class="font-semibold text-gold-light"> 9개 언어</span>
                  <span class="text-3xl font-semibold text-gold-light">
                    나눔 번역</span
                  >
                </p>
              </div>
              <div class="grid grid-col gap-4 text-right text-lg">
                <p>
                  Instagram 누적조회수 <br />
                  <span class="font-semibold text-3xl text-gold-light"
                    >700만</span
                  >
                  <br />
                  <span class="text-sm">
                    + 특수교사 등 학습장애 관련분야 전문가들과 소통
                  </span>
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 8: Bottom Wide Box -->
        <div class="col-span-6 row-span-3 col-start-7 row-start-1">
          <BentoCard>
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold"> 아키텍처 </span>
              </h1>
            </div>

            <NuxtImg src="/architecture.png" class="p-4" />

            <div class="text-lg mb-4">
              <p class="text-center">
                <span class="text-5xl font-semibold">PWA</span>
                프런트엔드 및 백엔드로 구성
              </p>
            </div>

            <tbody>
              <tr>
                <td class="px-4 font-semibold w-28">프런트엔드</td>
                <td class="px-4">
                  Nuxt.js, TailwindCSS, NuxtUI 프레임워크 등을 활용한
                  <span class="font-semibold">Server Side Rendering</span> 지원
                </td>
              </tr>
              <tr>
                <td class="px-4 py-2 font-semibold">백엔드</td>
                <td class="px-4 py-2">
                  <span class="font-semibold">Python FastAPI</span> 프레임워크
                  활용
                </td>
              </tr>
            </tbody>
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
