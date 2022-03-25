<template>
  <v-app>
    <topbar />

    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import topbar from "@/components/basicos/topbar.vue";

export default Vue.extend({
  name: "App",

  components: {
    topbar,
  },

  data: () => ({
    //
  }),
});
</script>
