<template>
  <nav class="navbar">
    <div class="container">
      <div class="navbar-brand">
        <h1 class="navbar-item">
          Margarita Chavez
        </h1>
      </div>

      <div id="navbarBasicExample" class="navbar-menu">
        <div class="navbar-start">
          <a class="navbar-item">
            Home
          </a>

          <a class="navbar-item">
            Writing Samples
          </a>

          <div class="navbar-item has-dropdown is-hoverable">
            <a class="navbar-link">
              Videos
            </a>

            <div class="navbar-dropdown">
              <a class="navbar-item">
                Vlogs
              </a>
              <a class="navbar-item">
                Movies
              </a>
              <a class="navbar-item">
                Interviews
              </a>
            </div>
          </div>
        </div>

        <div class="navbar-end">
          <div class="navbar-item">
            <div class="buttons">
              <a class="button is-danger">
                Contact
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>


  </nav>
</template>

<script>

export default {
  name: 'Navbar',
}
</script>

<style scoped>
h1 {
  letter-spacing: 0.2em;
  text-transform: uppercase;
  font-weight: bold;
}

</style>
