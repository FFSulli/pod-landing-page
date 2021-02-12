<template>
  <article class="hero__description">
    <h1 class="hero__description-title"><span class="hero__description-title--green">Publish your podcasts</span> everywhere.</h1>
    <p class="hero__description-paragraph">Upload your audio to Pod with a single click. We’ll then distribute your podcast to Spotify, Apple Podcasts, Google Podcasts, Pocket Casts and more!</p>
    <SubscribeInput></SubscribeInput>
    <CustomersList></CustomersList>
  </article>
</template>

<script>

import SubscribeInput from "@/components/SubscribeInput";
import CustomersList from "@/components/CustomersList";

export default {
  name: "Description",
  components: {
    SubscribeInput,
    CustomersList
  }
}
</script>
