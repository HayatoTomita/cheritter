<template>
  <v-app>
    <v-app-bar app>cheritter</v-app-bar>
    <v-main>
      <v-container>
        <tweetcard></tweetcard>
      </v-container>
    </v-main>
  </v-app>
</template>

<script>
import tweetcard from "./components/tweetcard";
export default {
  name: 'App',
  components: { tweetcard },
  data: () => ({
    //
  }),
};
</script>
