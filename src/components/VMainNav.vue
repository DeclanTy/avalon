<template>
  <nav>
    <v-app-bar>
      <router-link to="/">
        <v-img contain height="60" src="../assets/avalonlogo.svg" />
      </router-link>
      <span class="mx-2" contain max-height="30" max-width="30">Avalon</span>
    </v-app-bar>
  </nav>
</template>
<script>
export default {
  name: "MainNav",
  components: {},
  //give a formal name to the component
  data() {
    return {};
  },
  methods: {},
};
</script>
<style scoped></style>
