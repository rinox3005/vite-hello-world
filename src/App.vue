<script>
import AppTitle from "./components/AppTitleComponent.vue";
export default {
  name: "MyApp",
  data() {
    return {
      message: "Hello World",
    };
  },
  components: {
    AppTitle,
  },
};
</script>

<template>
  <main>
    <AppTitle />
  </main>
</template>

<style></style>
