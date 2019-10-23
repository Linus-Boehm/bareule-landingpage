<template lang="pug">
    .center-container
      .flex.flex-col.w-full
        .flex.w-full.justify-center.py-4
          nuxt-link.button.is-bareule(:to="'/'") Zurück
        h1.text-center.text-2xl Bleib auf dem laufenden und werde benachrichtigt wenn es los geht

</template>

<script>
export default {
name: "newsletter",
data( ){
    return {
    }
},
props: {},
methods: {},
computed: {},
}
</script>

<style scoped lang="scss">

</style>
