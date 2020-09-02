<template>
  <section class="hero is-info is-large">
    <div class="container">
      <div class="columns ">
        <div class="column">
          <div class="hero-body">
            <div class="introduction container">
              <h2 class="title">
                Director, Video Editor, Screen Writer
              </h2>
              <br>
              <p class="subtitle">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Accusantium commodi culpa ducimus eligendi
                explicabo
                harum laboriosam magni maiores maxime molestiae molestias, nisi nostrum obcaecati placeat provident quae
                quis
                quisquam repellendus reprehenderit, saepe sed sint sit soluta ullam veritatis voluptas voluptates?
                Aperiam ex
                excepturi facere in, officiis porro sed sunt voluptates.
              </p>
            </div>
          </div>
        </div>

        <div class="video-reel column">
          <iframe width="560" height="310" src="https://www.youtube.com/embed/KYSiuH8Ln4w" frameborder="0"
                  allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture"
                  allowfullscreen></iframe>
        </div>

      </div>
    </div>


  </section>
</template>

<script>
export default {
  name: 'Reel',
}
</script>

<style scoped>
.video-reel {
  display: flex;
  align-items: center;
  justify-content: center;
}
</style>
