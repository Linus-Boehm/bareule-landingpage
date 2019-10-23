<template lang="pug">
  .rootWrapper
    .comming-soon
      img(src="/comming_soon.svg")
    nuxt
</template>
<style scoped>
  .comming-soon{
    position: absolute;
    top: 0;
    right: 0;
  }
</style>
<style>
  html, body, .rootWrapper{
    background: #111111;
    box-shadow: inset 0px 0px 100px rgba(0,0,0,0.9);
    min-height: 100vh;
    min-width: 100vw;
    @apply font-serif;
  }

  .center-container{
    width: 100%;
    max-width: 600px;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translateY(-50%) translateX(-50%);
  }
</style>
