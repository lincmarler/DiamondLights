<template>
  <div class="container bg-dark">
    <section class="row">
      <div class="col-12 text-light">
        <h1>Revolutionizing Lighting</h1>
      </div>
      <div class="col-12 ">

      </div>
      <div class="col-12 text-center m-5">
        <h1>Day/night slider gang</h1>
      </div>
      <div class="m-5">
        <h1>Quote form</h1>
        <h3>Insert name here: </h3>
        <h3>Phone number: </h3>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  setup() {
    return {}
  }
}
</script>

<style scoped lang="scss">
.home {
  display: grid;
  height: 80vh;
  place-content: center;
  text-align: center;
  user-select: none;

  .home-card {
    width: 50vw;

    >img {
      height: 200px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
