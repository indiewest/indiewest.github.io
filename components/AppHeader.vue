<template>
    <div class="flex justify-between px-[24px] lg:px-[40px] py-[30px]">
      <NuxtLink to="/" class="hover:opacity-60 transition">
        <img src="~/assets/header-logo.svg" alt="logo" class="w-[200px]"/>
      </NuxtLink>
      <div class="flex w-[268px] md:w-[338px] lg:w-[468px] justify-between font-medium font-sans text-blue text-md lg:text-xl">
        <NuxtLink to="/team" class="hover:underline">TEAM</NuxtLink>
        <NuxtLink to="/works" class="hover:underline">WORKS</NuxtLink>
        <NuxtLink to="/contact" class="hover:underline">CONTACT</NuxtLink>
      </div>
    </div>
</template>

<style>
  .router-link-active {
    font-weight: bold;
  }
</style>