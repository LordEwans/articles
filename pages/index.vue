<template>
  <div
    class="bg-center bg-cover bg-[url('assets/img/wallpaperflare.com_wallpaper23.png')] bg-fixed"
  >
    <Hero />
    <div class="w-full flex justify-center bg-gray-800">
      <section class="">
        <div class="">
          <h1>Welcome to the Ace's Lobby</h1>
          <div class="lobbies">
            <h1 class="lobby">
              <nuxt-link to="/programming">Programming</nuxt-link>
            </h1>
            <p>
              <nuxt-link to="articles/how-i-became-a-better-programmer" class="articles"
                >How I Became a Better Programmer.</nuxt-link
              >
            </p>
            <h1 class="lobby"><nuxt-link to="/linux">Linux</nuxt-link></h1>
            <p>
              <nuxt-link to="/" class="articles"
                >The Best Linux Distros.</nuxt-link
              >
            </p>
            <p>
              <nuxt-link to="/" class="articles"
                >Why aren't people talking about openSUSE?</nuxt-link
              >
            </p>
            <h1 class="lobby">
              <nuxt-link to="/softwares">Softwares</nuxt-link>
            </h1>
            <p>
              <nuxt-link to="/" class="articles">
                5 Essential Softwares for Programmers.
              </nuxt-link>
            </p>
            <h1 class="lobby">
              <nuxt-link to="/projects">Projects</nuxt-link>
            </h1>
            <p>
              <nuxt-link to="/" class="articles"
                >Making an API for Tiktok Trends.</nuxt-link
              >
            </p>
            <p>
              <nuxt-link to="/" class="articles">What is Bottlehub?</nuxt-link>
            </p>
            <h1 class="lobby">
              <nuxt-link to="/off-topic">Off Topic</nuxt-link>
            </h1>
            <p>
              <nuxt-link to="/" class="articles"
                >Learning the Violin I.</nuxt-link
              >
            </p>
            <p>
              <nuxt-link to="/" class="articles"
                >Learning the Violin II.</nuxt-link
              >
            </p>
          </div>
        </div>
      </section>
    </div>
  </div>
</template>

<script lang="ts">
export default {};
</script>

<style>
.articles {
  @apply text-lg md:text-xl mb-2 font-semibold text-gray-400 uppercase;
}
h1 {
  @apply font-bold uppercase text-3xl md:text-4xl;
}
.lobby {
  @apply text-2xl md:text-3xl mb-2 mt-5 font-semibold text-gray-300 uppercase;
}
</style>
