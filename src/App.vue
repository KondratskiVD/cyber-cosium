<template>
  <div class="bg-hero">
    <div class="flex flex-col text-th-green z-10">
      <nav class="justify-between hidden px-3 pt-3 md:flex">
        <ul class="flex">
          <li class="mr-2">
            <router-link
                custom
                to="/"
                v-slot="{ href, navigate, isActive }"
            >
              <div class="button-notched text-xs flex"
                   :class="[isActive && 'active']">
                <span class="button-notched_corner button-notched_corner__left-top"></span>
                <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                <a :href="href" @click="navigate">ГОЛОВНА</a>
              </div>
            </router-link>
          </li>
          <li class="mr-2">
            <router-link
                custom
                to="/about"
                v-slot="{ href, navigate, isActive }"
            >
              <div class="button-notched text-xs flex"
                   :class="[isActive && 'active']">
                <span class="button-notched_corner button-notched_corner__left-top"></span>
                <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                <a :href="href" @click="navigate">ТЕСТИ</a>
              </div>
            </router-link>
          </li>
          <li>
            <router-link
                custom
                to="/contact"
                v-slot="{ href, navigate, isActive }"
            >
              <div class="button-notched text-xs flex"
                   :class="[isActive && 'active']">
                <span class="button-notched_corner button-notched_corner__left-top"></span>
                <span class="button-notched_corner button-notched_corner__right-bottom"></span>
                <a :href="href" @click="navigate">КОНТАКТИ</a>
              </div>
            </router-link>
          </li>
        </ul>
        <p class="text-cyber text-xl">CybeR &nbsp;&nbsp; Socium</p>
      </nav>
      <div class="flex-grow grid">
        <router-view/>
      </div>
    </div>
  </div>
</template>

<style lang="scss">
</style>
