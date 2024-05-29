<script>
export default {
  name: "AppHero",
};
</script>

<template>
  <div class="container">
    <img
      src="https://vitejs.dev/og-image-announcing-vite4-3.png"
      alt="vite-jumbo"
    />
  </div>
</template>

<style scoped>
.container {
  border-top: 2px solid #2a0d40;
  border-bottom: 2px solid #2a0d40;
  height: 600px;
}
img {
  object-fit: cover;
  overflow: hidden;
  height: 100%;
  width: 100%;
}
</style>
