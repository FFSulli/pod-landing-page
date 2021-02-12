<template>
  <div id="app">
    <main class="hero">
      <Logo></Logo>
    </main>

  </div>
</template>

<script>
import Logo from "@/components/Logo";

export default {
  name: 'App',
  components: {
    Logo,
  }
}
</script>

<style lang="scss">
@import "src/assets/scss/main.scss";

</style>
