<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-dark px-3">
    <router-link class="navbar-brand d-flex" :to="{ name: 'Home' }">
      <div class="d-flex flex-column align-items-center">
        <h1><i class="mdi mdi-diamond"></i>Diamond Lights</h1>
      </div>
    </router-link>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarText"
      aria-controls="navbarText" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarText">
      <ul class="navbar-nav me-auto">

        <li>
          <router-link :to="{ name: 'Residential' }" class="btn text-success lighten-30 selectable text-uppercase">
            Residential
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Commercial' }" class="btn text-success lighten-30 selectable text-uppercase">
            Commercial
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Contact Us' }" class="btn text-success lighten-30 selectable text-uppercase">
            Contact Us!
          </router-link>
        </li>
        <li>
          <router-link :to="{ name: 'Our Process' }" class="btn text-success lighten-30 selectable text-uppercase">
            Our Process
          </router-link>
        </li>
      </ul>
      <!-- LOGIN COMPONENT HERE -->

    </div>
  </nav>
</template>

<script>
export default {
  setup() {
    return {}
  },
  components: {}
}
</script>

<style scoped>
a:hover {
  text-decoration: none;
}

.nav-link {
  text-transform: uppercase;
}

.navbar-nav .router-link-exact-active {
  border-bottom: 2px solid var(--bs-success);
  border-bottom-left-radius: 0;
  border-bottom-right-radius: 0;
}

@media screen and (min-width: 768px) {
  nav {
    height: 64px;
  }
}
</style>
