<template>
  <div style="min-height: 90vh">
    <div
      class="container d-flex flex-col items-center justify-center"
      style="min-height: 90vh"
    >
      <div class="form bg-gray-800 pa-3 rounded-lg w-1/3">
        <v-text-field label="Username" class="ma-0"> </v-text-field>
        <v-text-field
          label="Password"
          type="password"
          class="ma-0"
          append-icon="mdi-eye"
        >
        </v-text-field>
        <v-btn class="w-full"> LOGIN </v-btn>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {}
  },
}
</script>
