<template>
  <v-row>
    <v-col cols="8" offset="2">
      <v-text-field
        label="Search"
        append-icon="mdi-magnify"
        solo
        flat
      ></v-text-field>
    </v-col>
    <v-col cols="10" offset="1">
      <v-row>
        <v-col xs=12 sm="12" md="6" lg="3" class="had-title">
          <h1><v-icon class="had-icon">mdi-fire</v-icon> {{ title | clz }} </h1>
        </v-col>
      </v-row>
    </v-col>
  </v-row>
</template>

<script>
export default {
  data: () => ({
    title: 'Articles'
  }),
  computed: {
    changeTitleHad(title) {
      this.title = title
    }
  }
}
</script>

<style lang="scss" scoped>
   .had-title {
      display: flex;
      align-items: center;
      align-content: center;
      .had-icon {
        font-size: 2.5rem;
        color: #141414;
      }
   }
</style>
