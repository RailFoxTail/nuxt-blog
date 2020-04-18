<template>
  <v-app>
    <drawer />
    <v-content>
      <v-container fluid>
        <nuxt />
      </v-container>
    </v-content>

    <v-footer app>
    </v-footer>
  </v-app>
</template>

<script>

import Drawer from '@/components/drawer'
export default {
  components: {
    Drawer
  }
}
</script>

<style>
</style>
