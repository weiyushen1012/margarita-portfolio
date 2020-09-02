<template>
  <div class="box">
    <h3>{{ video.title }}</h3>
    <iframe width="400" height="220" v-bind:src="video.url"
            allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>
</template>

<script>
export default {
  name: 'Video',
  props: ['video'],
}
</script>

<style scoped>
.box {
  width: 450px;
}
</style>
