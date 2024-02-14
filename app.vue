<template>
  <div>
    <NuxtLayout />
  </div>
</template>

<style>
.page-enter-active,
/* .page-leave-active {
  transition: all 0.2s;
} */
.page-enter-from,
.page-leave-to {
  opacity: 0;
}

::selection {
  background-color: #0025DE;
  color: #fff;
}
</style>