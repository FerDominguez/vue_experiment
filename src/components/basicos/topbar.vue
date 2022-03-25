<template>
  <div>
    <v-app-bar color="deep-purple accent-4" dense dark>
      <v-app-bar-nav-icon
        ><router-link to="/">LOGO</router-link></v-app-bar-nav-icon
      >

      <v-toolbar-title>Page title</v-toolbar-title>

      <v-spacer></v-spacer>

      <div class="input-group">
        <input
          type="text"
          class="form-control"
          aria-label="Text input with segmented dropdown button"
        />
        <button type="button" class="btn btn-outline-secondary">Action</button>
        <button
          type="button"
          class="
            btn btn-outline-secondary
            dropdown-toggle dropdown-toggle-split
          "
          data-bs-toggle="dropdown"
          aria-expanded="false"
        >
          <span class="visually-hidden">Toggle Dropdown</span>
        </button>
        <ul class="dropdown-menu dropdown-menu-end">
          <li><a class="dropdown-item" href="#">Action</a></li>
          <li><a class="dropdown-item" href="#">Another action</a></li>
          <li><a class="dropdown-item" href="#">Something else here</a></li>
          <li><hr class="dropdown-divider" /></li>
          <li><a class="dropdown-item" href="#">Separated link</a></li>
        </ul>
      </div>
      <v-btn icon>
        <v-icon>mdi-magnify</v-icon>
      </v-btn>
    </v-app-bar>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>