<template>
  <div class="_df _jcsb _mvxs">
    <NuxtLink to="/">
      <span>lincoln</span>
      <span class="_fw7">vasselai</span>
    </NuxtLink>
    <div>
      <NuxtLink to="/" class="navbarLink">Sobre</NuxtLink>
      <NuxtLink to="/" class="navbarLink">Trabalho</NuxtLink>
      <NuxtLink to="/" class="navbarLink">Contato</NuxtLink>
    </div>
  </div>
</template>

<style lang="scss">
.navbarLink {
  margin-left: 32px;
  font-weight: 700;
  position: relative;

  &:after {
    content: "";
    position: absolute;
    width: 100%;
    opacity: 0;
    height: 1px;
    background-color: black;
    left: 0;
    bottom: 0;
    transition: ease-in opacity 0.3s;
  }

  &:hover:after {
    opacity: 100%;
  }
}
</style>
