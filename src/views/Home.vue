<template>
  <div class="home">
    <div>
      <country-flag country="it" size="big" />
      <country-flag country="hr" size="big" />
      <country-flag country="fr" size="big" />
      <country-flag country="rus" size="big" />
    </div>
    <img alt="Vue logo" src="../assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import CountryFlag from "vue-country-flag";

export default {
  name: "Home",
  components: {
    HelloWorld,
    CountryFlag,
  },
};
</script>
