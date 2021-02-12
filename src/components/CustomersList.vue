<template>
<div class="hero__description-customers">
  <IconSpotify></IconSpotify>
  <IconApplePodcast></IconApplePodcast>
  <IconGooglePodcasts></IconGooglePodcasts>
  <IconPocketCasts></IconPocketCasts>
</div>

</template>

<script>
import IconSpotify from "@/components/Icons/IconSpotify";
import IconApplePodcast from "@/components/Icons/IconApplePodcast";
import IconGooglePodcasts from "@/components/Icons/IconGooglePodcasts";
import IconPocketCasts from "@/components/Icons/IconPocketCasts";

export default {
  name: "CustomersList",
  components: {
    IconSpotify,
    IconApplePodcast,
    IconGooglePodcasts,
    IconPocketCasts
  }
}
</script>