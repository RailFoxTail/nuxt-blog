<template>
  <v-card
    elevation="6"

  >
    <v-img
      class="white--text align-end"
      height="200px"
      src="https://cdn.vuetifyjs.com/images/cards/docks.jpg"
    >
    </v-img>
    <v-card-title>Post title</v-card-title>
    <v-card-actions>
      <v-card-subtitle>
        {{new Date().toLocaleString()}}
      </v-card-subtitle>
      <v-spacer></v-spacer>
      <v-btn fab small text @click="openArticle">
        <v-icon>mdi-resize</v-icon>
      </v-btn>
    </v-card-actions>
  </v-card>
</template>

<script>
export default {

}
</script>

<style>

</style>
