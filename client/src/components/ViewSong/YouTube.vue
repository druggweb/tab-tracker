<template>
  <panel title="YouTube Video">
    <youtube
      :video-id="youtubeId"
      :player-width="560"
      :player-height="315">
    </youtube>
  </panel>
</template>

<script>
export default {
  props: [
    'youtubeId'
  ]
}
</script>

<style scoped>
</style>
