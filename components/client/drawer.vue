<template>
    <v-navigation-drawer
      app
      width="80"
      class="drawer-wrapper"
    >
      <v-list-item>
        <v-list-item-content>
          <v-list-item-title  class="drawer-title">
            <v-icon class="drawer-title-icon">mdi-tower-fire</v-icon>
            <span>tower fire</span>
          </v-list-item-title>
        </v-list-item-content>
      </v-list-item>
    </v-navigation-drawer>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>
  .drawer-title {

    display: flex;
    justify-content: center;
    flex-direction: column;

    .drawer-title-icon {
      font-size: 2rem;
      color: #3f3f3f
    }

    span {
      margin-top: 10px;
      font-size: 0.53rem;
      font-weight: bold;
      text-transform: uppercase;
    }
  }
</style>
