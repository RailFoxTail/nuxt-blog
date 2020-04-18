<template>
  <v-row>
    <v-col
      xs="12"
      sm="6"
      md="3"
      lg="3"
      xl="2"

      v-for="c of 1" :key="c"

    >
      <Article />
    </v-col>
  </v-row>
</template>

<script>

import Article from '@/components/client/post'
export default {
  head: {
    title: 'Home'
  },
  components: {
    Article
  },
  methods: {
    emitHadTitle() {
      this.$emit('emitHadTitle', 'Articles')
    }
  }
}
</script>

<style>

</style>
