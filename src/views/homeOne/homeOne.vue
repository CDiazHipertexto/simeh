<template lang="pug">
  //Layout
  #content
    navigationSimeh
    main.prehome
      article
        immedi-delivery
</template>

<script>

import immediDelivery from "@/components/page/home/immedi-delivery";
import navigationSimeh from '@/components/layout/nav/navigationSimeh';

export default {
  name: 'home-one',
  components: { immediDelivery, navigationSimeh},
  data() {
    return {

    }
  },
  methods: {

  },
  computed: {

  },
  watch: {

  },
  mounted() {

  }
}
</script>
<style lang="sass" scoped>
  h1
    background-color: blue
</style>
