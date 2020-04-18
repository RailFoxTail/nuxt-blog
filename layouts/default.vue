<template>
  <v-app>
    <drawer />
    <v-content>
      <had  v-on:emitHadTitle="changeTitleHad"/>
      <v-container fluid>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer app>
    </v-footer>
  </v-app>
</template>

<script>

import Drawer from '@/components/client/drawer'
import Had from '@/components/client/had'
export default {
  components: {
    Drawer,
    Had
  }
}
</script>

<style>
</style>
