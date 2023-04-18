<template>
  <div>
    <div class="container-notched bg-gero__mobile border-th-green mx-3 container-notched__specific-corner flex justify-center items-center flex-wrap my-3" style="height: calc(100vh - 66px)">
      <span class="container-notched_corner container-notched_corner__left-bottom bg-th-green"></span>
      <span class="container-notched_corner container-notched_corner__right-top bg-th-green"></span>
      <span class="container-notched_corner container-notched_corner__right-bottom bg-th-green"></span>

      <div class="container-notched__specific-corner-half border-gray-400">
        <span class="container-notched_corner__mini container-notched_corner__mini__right-top bg-gray-400"></span>
      </div>
      <span class="left-dots flex flex-col gap-4">
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                </span>
      <span class="right-dot bg-gray-400"></span>

      <div class="pt-48 md:pt-64 flex flex-col items-center px-3 text-center">
        <p class="text-sm md:text-6xl font-bold text-white shadow-black text-opacity-90">ПСИХОЛОГІЧНІ</p>
        <p class="text-xl md:text-9xl font-bold glow">КІБЕР ТЕСТИ</p>
        <p class="text-xs md:text-2xl mt-2 text-white text-opacity-90">ПРОСКАНУЙ СВОЄ "Я"</p>
        <a href="#About-Me"
           class="scroll-button mx-auto bounce">
            <div class="text-4xl">▾</div>
        </a>
      </div>
    </div>
    <div class="my-3 container-notched__pained mx-3 bg-th-green py-6 md:py-16 px-6 md:px-24 flex flex-col md:flex-row items-center justify-between">
      <div>
        <p class="font-bold text-th-dark text-3xl">Обери свій тест</p>
        <p class="text-sm font-bold mt-1 text-th-dark ">Всі тести обрані з наукових джерел та доказали <br>свою  точність прогнозування до 85% [ 1 ]</p>
      </div>
      <p class="text-cyber text-th-dark text-2xl md:text-7xl">CybeR&nbsp;&nbsp; Socium</p>
    </div>

    <div class="pt-16 md:px-24 relative bg-grid-lines px-3">
      <p class="font-bold text-th-green text-2xl md:text-5xl">На любий смак</p>
      <p class="text-sm font-bold mt-1 text-gray-300">Всі тести обрані з наукових джерел та доказали <br>свою  точність прогнозування до 85% [ 1 ]</p>
      <div class="text-chunk grid md:grid-cols-3 gap-12 mt-12">
        <div class="card-test">
          <div class="container-notched border-th-green container-notched__specific-corner-2">
            <span class="container-notched_corner container-notched_corner__left-bottom bg-th-green"></span>
            <span class="container-notched_corner container-notched_corner__right-top bg-th-green"></span>
            <div class="img-test-1 h-72 p-3">
              <div class="container-notched container-notched__specific-corner-half border-gray-400">
                <span class="container-notched_corner__mini container-notched_corner__mini__right-top bg-gray-400"></span>
              </div>
              <span class="left-dots flex flex-col gap-4">
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                </span>
              <span class="right-dot bg-gray-400"></span>
            </div>
          </div>
            <span class="notched__left-bottom bg-gray-700"></span>
            <span class="notched__right-top bg-gray-700"></span>
            <p class="text-th-green text-bold text-2xl mt-3">Профорієнтаційні тести</p>
            <div class="mt-3 flex">
              <router-link
                  custom
                  to="/test"
                  v-slot="{ href, navigate, isActive }"
              >
                <div class="button-notched text-xs flex"
                     :class="[isActive && 'active']">
                  <span class="button-notched_corner button-notched_corner__left-top"></span>
                  <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                  <a :href="href" @click="navigate">ПЕРЕЙТИ</a>
                </div>
              </router-link>
            </div>
            <ul class="text-gray-300 text-sm mt-2">
              <li class="list-item">Допомагають з вибором професії</li>
              <li class="list-item">Визначать твій професійний психотип</li>
              <li class="list-item">Показують твоє справжне бажання - ким ти хочеш бути</li>
            </ul>
        </div>
        <div class="card-test">
          <div class="container-notched border-th-green container-notched__specific-corner-2">
            <span class="container-notched_corner container-notched_corner__left-bottom bg-th-green"></span>
            <span class="container-notched_corner container-notched_corner__right-top bg-th-green"></span>
            <div class="img-test-3 h-72 p-3">
              <div class="container-notched h-1/2 container-notched__specific-corner-half border-gray-400">
                <span class="container-notched_corner__mini container-notched_corner__mini__right-top bg-gray-400"></span>
              </div>
              <span class="left-dots flex flex-col gap-4">
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                </span>
              <span class="right-dot bg-gray-400"></span>
            </div>
          </div>
          <span class="notched__left-bottom bg-gray-700"></span>
          <span class="notched__right-top bg-gray-700"></span>
          <p class="text-th-green text-bold text-2xl mt-3">Профорієнтаційні тести</p>
          <div class="mt-3 flex">
            <router-link
                custom
                to="/test"
                v-slot="{ href, navigate, isActive }"
            >
              <div class="button-notched text-xs flex"
                   :class="[isActive && 'active']">
                <span class="button-notched_corner button-notched_corner__left-top"></span>
                <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                <a :href="href" @click="navigate">ПЕРЕЙТИ</a>
              </div>
            </router-link>
          </div>
          <ul class="text-gray-300 text-sm mt-2">
            <li class="list-item">Допомагають з вибором професії</li>
            <li class="list-item">Визначать твій професійний психотип</li>
            <li class="list-item">Показують твоє справжне бажання - ким ти хочеш бути</li>
          </ul>
        </div>
        <div class="card-test">
          <div class="container-notched border-th-green container-notched__specific-corner-2">
            <span class="container-notched_corner container-notched_corner__left-bottom bg-th-green"></span>
            <span class="container-notched_corner container-notched_corner__right-top bg-th-green"></span>
            <div class="img-test-2 h-72 p-3">
              <div class="container-notched h-1/2 container-notched__specific-corner-half border-gray-400">
                <span class="container-notched_corner__mini container-notched_corner__mini__right-top bg-gray-400"></span>
              </div>
              <span class="left-dots flex flex-col gap-4">
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                  <span class="dot bg-gray-400"></span>
                </span>
              <span class="right-dot bg-gray-400"></span>
            </div>
          </div>
          <span class="notched__left-bottom bg-gray-700"></span>
          <span class="notched__right-top bg-gray-700"></span>
          <p class="text-th-green text-bold text-2xl mt-3">Профорієнтаційні тести</p>
          <div class="mt-3 flex">
            <router-link
                custom
                to="/test"
                v-slot="{ href, navigate, isActive }"
            >
              <div class="button-notched text-xs flex"
                   :class="[isActive && 'active']">
                <span class="button-notched_corner button-notched_corner__left-top"></span>
                <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                <a :href="href" @click="navigate">ПЕРЕЙТИ</a>
              </div>
            </router-link>
          </div>
          <ul class="text-gray-300 text-sm mt-2">
            <li class="list-item">Допомагають з вибором професії</li>
            <li class="list-item">Визначать твій професійний психотип</li>
            <li class="list-item">Показують твоє справжне бажання - ким ти хочеш бути</li>
          </ul>
        </div>
      </div>
      <footer class="h-24 flex justify-between items-center">
        <p class="text-cyber text-xl text-white">CybeR &nbsp;&nbsp; Socium</p>
        <ul class="flex">
          <li class="mr-3"><i class="fa-brands fa-tiktok text-th-green"></i></li>
          <li class="mr-3"><i class="fa-brands fa-youtube text-th-green"></i></li>
          <li class=""><i class="fa-brands fa-instagram text-th-green"></i></li>
        </ul>
      </footer>
    </div>


<!--    <div class="container-notched container-notched__pained grid my-3" style="height: calc(100vh - 66px)">-->
<!--      <span class="notched__left-top"></span>-->
<!--      <span class="notched__left-bottom"></span>-->
<!--      <span class="notched__right-top"></span>-->
<!--      <span class="notched__right-bottom"></span>-->
<!--      <div class="text-chunk text-transparent-black">-->
<!--          важливе повідомлення-->
<!--      </div>-->
<!--      <div class="divide-y-4 divide-black divide-opacity-25">-->

<!--      </div>-->
<!--      <div class="text-cyber text-transparent-black">-->
<!--        важливе повідомлення-->
<!--      </div>-->
<!--    </div>-->
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'

export default {
  name: 'Home',
  components: {

  }
}
</script>
