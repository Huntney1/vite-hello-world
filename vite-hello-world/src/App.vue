<script>
import TitleApp from "./components/TitleApp.vue";
import AppHero from "./components/AppHero.vue";

export default {
  components: {
    TitleApp,
    AppHero,
  },
};
</script>

<template>
  <div class="bordi">
    <TitleApp />
    <AppHero />
  </div>
</template>

<style scope>
.bordi{
  width: 15em;
  height: 5em;
  padding-top: 1.5em;
  border: 2px solid white;

}
</style>
