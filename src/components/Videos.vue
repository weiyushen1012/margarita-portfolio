<template>
  <div class="container">
    <div class="videos">
      <div v-for="video in videos" v-bind:key="video.id">
        <Video v-bind:video="video" />
      </div>
    </div>
  </div>
</template>

<script>
import videos from '../assets/videos.json'
import Video from './Video'

export default {
  name: 'Videos',
  components: { Video },
  data() {
    return {
      videos,
      Video,
    }
  },
}
</script>

<style scoped>
.videos {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  grid-gap: 1em;
  margin: 1em;
}

</style>
