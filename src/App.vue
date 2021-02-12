<template>
  <div id="app">
    <main class="hero">
      <Logo></Logo>
      <Description></Description>
    </main>

  </div>
</template>

<script>
import Logo from "@/components/Logo";
import Description from "@/components/Description";

export default {
  name: 'App',
  components: {
    Logo,
    Description
  }
}
</script>

<style lang="scss">
@import "src/assets/scss/main.scss";

</style>
