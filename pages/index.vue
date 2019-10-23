<template lang="pug">
  .w-full.h-full


    .center-container
      .flex.flex-col.w-full
        .flex.w-full.justify-center
          img(src="/logo.svg")

        h1.mt-4.p-8.text-center.font-sans.pt-4.text-2xl MÜNCHENS SCHÖNSTE BARS & KNEIPEN FINDEN
        .flex.w-full.justify-center.pt-4
          //nuxt-link.button.is-bareule(:to="'/newsletter'") Wann geht`s los?

</template>

<script>
import Logo from '~/components/Logo.vue'

export default {
  components: {
    Logo
  }
}
</script>

<style scoped="true">


</style>
