<template>
  <div>
    <v-card
      class="overflow-hidden"
      color="transparent"
    >
      <v-app-bar
        absolute
        elevate-on-scroll
      >
        <v-app-bar-nav-icon @click="drawer = true" />

        <v-toolbar-title>รายชื่อนักเรียนทั้งหมด</v-toolbar-title>
      </v-app-bar>
      <Nuxt />
    </v-card>
  </div>
</template>
<script>
export default {
  data: () => ({
    drawer: false,
    group: null
  })
}
</script>
