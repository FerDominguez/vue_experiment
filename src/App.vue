<template>
  <v-app>
    <topbar />
    <v-container fluid>
      <v-row class="clearfix">
        <sidemenu class="float-md-start col-auto" />
        <v-main>
          <router-view />
        </v-main>
      </v-row>
    </v-container>
  </v-app>
</template>

<script lang="ts">
import Vue from "vue";
import topbar from "@/components/basicos/topbar.vue";
import sidemenu from "@/components/basicos/sidemenu.vue";

export default Vue.extend({
  name: "App",

  components: {
    topbar,
    sidemenu,
  },

  data: () => ({
    //
  }),
});
</script>
