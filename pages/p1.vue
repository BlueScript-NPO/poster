<template>
  <div class="w-full h-screen bg-white text-zinc-950 break-keep">
    <ScalingPoster>
      <div
        class="p-6 w-full h-full bg-white grid grid-cols-12 grid-rows-6 gap-4"
      >
        <!-- Box 1: Top Left Small Box -->
        <div class="col-span-3 row-span-2 col-start-7 row-start-3">
          <BentoCard
            class="border-none border-none bg-gradient-to-b from-zinc-800 to-black text-white text-white"
          >
            <div class="w-full flex justify-center mb-4">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">난독증</span>과의
                <span class="font-semibold">투쟁</span>
              </h1>
            </div>

            <p class="italic pb-2 text-xl text-right mb-6">
              저는 난독증과 아직 사투를 <br />
              벌이고 있습니다.
            </p>

            <p class="pb-2 text-lg">
              <span class="text-5xl font-semibold text-negative">난독증</span
              >(難讀症): 글은 읽을 수는 있지만 <br />글을 읽고 이해하는데
              어려움이 있는 학습 장애
            </p>

            <p class="pb-2 text-lg">
              중학교 입학 무렵
              <span class="text-5xl font-semibold text-negative">2년</span> 간
              집중 훈련 덕에<br />
              어느 정도 극복에 성공.
            </p>
            <p class="text-lg">
              그렇지만
              <span class="font-semibold text-negative">시기가 늦어</span><br />
              완전한 극복은 하지 못함.
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
                <span class="font-semibold">숫자</span>로 보는
                <span class="font-semibold">난독증</span>
              </h1>
            </div>

            <div class="flex justify-between w-full">
              <div class="flex flex-col space-y-3">
                <p class="text-xl">
                  전 세계 인구의 약
                  <span class="text-5xl font-semibold text-negative">5%</span>
                </p>
                <p class="text-xl">
                  골든 타임 만
                  <span class="text-5xl font-semibold text-negative">12세</span>
                </p>
              </div>
              <div class="grid grid-col gap-4 text-right text-lg">
                <p>
                  의료보험
                  <span class="font-semibold text-negative">사각지대</span>
                </p>
                <p>
                  부담 되는
                  <span class="font-semibold text-negative">훈련 비용</span>
                </p>
                <p>
                  <span class="font-semibold text-negative"
                    >해외기업 솔루션</span
                  >의 부족한
                  <span class="font-semibold text-negative">한글화</span>
                </p>
              </div>
            </div>
          </BentoCard>
        </div>

        <!-- Box 3: Top Right Small Box -->
        <div class="col-span-3 row-span-3 col-start-10 row-start-4">
          <BentoCard
            class="bg-gradient-to-b from-zinc-50 to-zinc-100 text-zinc-800"
          >
            <div class="w-full flex justify-center pb-12">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">영감</span>의
                <span class="font-semibold">가능성</span>
              </h1>
            </div>

            <div class="text-lg space-y-4">
              <p>
                <span class="text-5xl font-semibold text-gold-light">1.</span>
                누구나 컴퓨터만 있으면 난독증 훈련을 할 수 있다.
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light">2.</span>
                누구나 자유롭게 소프트웨어에 사용된 코드를 수정/보완하고 <br />
                공유할 수 있어야 한다.
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light">3.</span>
                개인이 통제 하는 것이 아닌 커뮤니티가 함께 프로그램 개발에
                참여한다.
              </p>
            </div>

            <div class="w-full flex py-6 justify-center">
              <icon name="i-ph-arrow-down" class="text-2xl" />
            </div>

            <div class="space-y-4">
              <p>
                <span class="text-5xl font-semibold text-gold-light">웹 앱</span
                >으로 <br />
                플랫폼과 장소의<br />
                구애 없이 쉽게 훈련
              </p>
              <p>
                <span class="text-5xl font-semibold text-gold-light"
                  >오픈소스</span
                ><br />모델 적용
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 4: Large Center Box -->
        <div class="col-span-6 row-span-4 col-start-1 row-start-1">
          <BentoCard
            class="relative bg-blueScriptBlue-700 text-white border-none"
          >
            <!-- Mockup Image -->
            <div class="absolute inset-0">
              <NuxtImg src="/mockup-1.png" class="w-full h-full object-cover" />
            </div>

            <!-- Overlay with Logo and Text -->
            <div
              class="relative z-10 w-full flex justify-center items-center h-[30%] flex-col text-center p-4"
            >
              <NuxtImg src="/logo-dark.svg" class="w-[23%]" />
              <p class="mt-4 font-normal text-3xl mb-6">
                난독증 개선을 위한
                <span class="text-6xl font-semibold">뇌과학 방법론</span> 기반
                훈련 프로그램
              </p>

              <p class="text-2xl">코딩하는선비</p>
              <p class="italic text-sm">고요한 아침의 개발자</p>
            </div>

            <!-- Small Text Box: Bottom Left Corner -->
            <div class="absolute bottom-2 right-2">
              <p class="text-xs text-zinc-100">(자체 제작)</p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 5: Middle Left Tall Box -->
        <div class="col-span-3 row-span-2 col-start-10 row-start-2">
          <BentoCard>
            <div class="w-full flex justify-center pb-16">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">영감</span>의
                <span class="font-semibold">근원</span>
              </h1>
            </div>

            <div>
              <p class="text-left text-lg">
                <span class="font-semibold">소프트웨어 배포</span> 비용은
                <span class="text-5xl font-semibold">0에</span> 수렴 할 수
                있지만 소프트웨어는
                <span class="font-semibold"
                  >누군가의 삶에 <br />
                  큰 영향을 미칠 수 있다</span
                >
              </p>
            </div>

            <div class="w-full flex py-6 justify-center">
              <icon name="i-ph-x" class="text-2xl" />
            </div>

            <div>
              <p class="text-left text-lg">
                <span class="font-semibold">난독증</span>이 받을 수 있는
                <span class="text-5xl font-semibold">도움</span> 은 있기는 할까?
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 6: Middle Right Tall Box -->
        <div class="col-span-3 row-span-2 col-start-1 row-start-5">
          <BentoCard class="px-6">
            <div class="w-full flex justify-center">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">신경 가소성</span>
              </h1>
            </div>
            <p class="italic text-md text-right pb-20">(Synaptic Plasticity)</p>

            <div>
              <p class="text-left text-xl">
                일반적으로 책을 읽을 때 받을 수 없는 <br />
                강하고 반복적인
                <span class="text-5xl font-semibold"> 자극</span>을 이용해
                독서할 때 정보 전달을 원활하게 하는
                <span class="text-5xl font-semibold">신경회로</span>가 형성
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 7: Bottom Center Medium Box -->
        <div class="col-span-6 row-span-2 col-start-4 row-start-5">
          <BentoCard>
            <div class="w-full flex justify-center pb-8">
              <h1 class="text-3xl font-semibold">새로운 관점</h1>
            </div>

            <div class="text-lg text-center">
              <p class="mb-4">
                난독증의 문제를 언어학적 관점 대신<br />
                <span class="text-5xl font-semibold">뇌과학적</span> 관점으로
                접근
              </p>
              <p>
                난독증은 읽기를 담당하는<br />
                뇌 영역끼리 연결하는 읽기 회로가 비효율적 으로 구성됨
              </p>
            </div>

            <div class="w-full flex py-6 pt-8 justify-center">
              <icon name="i-ph-arrow-down" class="text-2xl" />
            </div>

            <div class="text-lg space-y-4 text-center">
              <p>
                <span class="text-5xl font-semibold">신경 가소성</span>을 이용해
                <br />
                비효율적인 읽기 회로를<br />
                <span class="text-5xl font-semibold">효율적으로 재구성</span>
              </p>
            </div>
          </BentoCard>
        </div>

        <!-- Box 8: Bottom Wide Box -->
        <div class="col-span-3 row-span-1 col-start-7 row-start-2">
          <BentoCard>
            <div class="w-full flex justify-center pb-6">
              <h1 class="text-3xl font-normal">
                <span class="font-semibold">더 알아보기</span>
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
