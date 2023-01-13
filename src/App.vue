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
    <p class="title">
      <TitleApp />
    </p>

    <AppHero />
  </div>
</template>

<style lang="scss" scope>
.bordi {
  width: 15em;
  height: 5em;
  border: 2px solid white;
  
}
.bordi:hover{
  display: none;
  background-color: rgb(0, 0, 0);
}

.bordi:hover {
  color: aquamarine;
  border: 3px solid aquamarine;
  display: block;
}

.title:hover {
  text-shadow: 1.5px 2px 3px blue;
}
</style>
