<template>
  <div>
    <v-app-bar color="#A1DBB2" dense dark>
      <v-app-bar-nav-icon
        ><router-link to="/"
          ><v-icon class="colorIn">mdi-book</v-icon></router-link
        ></v-app-bar-nav-icon
      >

      <v-toolbar-title>Open Books</v-toolbar-title>

      <v-spacer></v-spacer>

      <div class="input-group busqueda">
        <input
          type="text"
          class="form-control colorIn"
          placeholder="Type to Search"
        />
        <button type="button" class="btn btn-outline-secondary colorIn">
          <v-icon class="colorIn">mdi-magnify</v-icon>
        </button>
      </div>
    </v-app-bar>
  </div>
</template>

<script>
export default {};
</script>

<style>
.colorIn {
  background-color: transparent !important;
  border-color: transparent !important;
  color: white !important;
}

.colorIn:hover {
  background-color: transparent !important;
  border-color: rgba(244, 93, 76, 1) !important;
  color: #f45d4c !important;
}

.colorIn:focus {
  background-color: transparent !important;
  border-color: rgba(244, 93, 76, 0.5) !important;
  color: #f45d4c !important;
}

.busqueda {
  width: 350px !important;
}
@media (max-width: 768px) {
  .busqueda {
    width: 250px !important;
  }
}
@media (max-width: 576px) {
  .busqueda {
    width: 150px !important;
  }
}
</style>