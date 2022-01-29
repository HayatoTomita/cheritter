<template>
  <v-app>
    <v-main>
      <tweetcard></tweetcard>
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
