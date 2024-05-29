<script>
import AppTitle from "./components/AppTitleComponent.vue";
import AppHero from "./components/AppHeroComponent.vue";
import AppFooter from "./components/AppFooterComponent.vue";
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
    AppFooter,
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
  <footer>
    <AppFooter />
  </footer>
</template>

<style></style>
