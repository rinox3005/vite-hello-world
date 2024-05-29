<script>
import AppTitle from "./components/AppTitleComponent.vue";
import AppHero from "./components/AppHeroComponent.vue";
export default {
  name: "MyApp",
  data() {
    return {
      message: "Hello World",
    };
  },
  components: {
    AppTitle,
    AppHero,
  },
};
</script>

<template>
  <header>
    <AppTitle />
  </header>
  <main>
    <AppHero />
  </main>
</template>

<style></style>
