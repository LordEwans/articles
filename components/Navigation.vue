<template>
  <header class="grid grid-cols-2 py-[.2em] w-full z-30 will-change-transform">
    <div class="mx-[1.5em] my-[1em] md:mx-[2em] md:my-[1em] block text-base md:text-lg">
      <nuxt-link to="https://lordewans.github.io/" class="uppercase font-black text-white"
        >Lord Ewan</nuxt-link
      >
    </div>
    <nav class="flex justify-self-end">
      <ul class="flex">
        <li>
          <nuxt-link to="https://lordewans.github.io/#contact" class="partials">Contact</nuxt-link>
        </li>
        <li>
          <nuxt-link to="https://lordewans.github.io/articles" class="partials">Articles</nuxt-link>
        </li>
      </ul>
      <!-- <button>
        <img src="assets/img/animated/day.svg" alt="Default" />
      </button> -->
    </nav>
  </header>
</template>

<style>
li {
  @apply inline mx-2 md:mx-8 my-4;
}
.partials {
  @apply inline-block uppercase font-bold text-white text-xs md:text-sm;
}
</style>
