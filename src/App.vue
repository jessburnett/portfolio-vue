<template>
  <v-app>
    <v-content>
      <Home />
    </v-content>
  </v-app>
</template>

<script>
import Home from "@/views/Home";
import "@/views/Home.scss";

navigator.serviceWorker.register('./service-worker.js');

export default {
  name: "App",
  components: {
    Home
  },
  data: () => ({
    //
  })
};
</script>
