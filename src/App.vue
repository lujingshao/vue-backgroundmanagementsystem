<template>
  <div id="app">
    <router-view></router-view>
  </div>
</template>

<style lang="scss" scoped>
  @import "@/static/globalStyle/index";
  #app{
    @include box(100%,100%);
  }
</style>
