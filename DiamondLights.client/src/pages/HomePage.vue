<template>
  <div class="container bg-dark">
    <section class="row">
      <div class="col-12 text-light">
        <h1>Revolutionizing Lighting!</h1>
      </div>
      <div class="col-12">
        <img
          src="https://images.unsplash.com/photo-1573757747798-62adbde0f981?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8NHx8Y2hyaXN0bWFzJTIwbGlnaHRzfGVufDB8fDB8fHww&auto=format&fit=crop&w=600&q=60"
          alt="" class="img">
      </div>
      <div class="col-12 text-center m-5">
        <h1>Day/night slider gang</h1>
        <img
          src="https://images.unsplash.com/photo-1606757490005-e9cfe1c4e43e?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTJ8fGNocmlzdG1hcyUyMGxpZ2h0c3xlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=600&q=60"
          alt="">
        <img
          src="https://images.unsplash.com/photo-1543516352-d4d7a2b39714?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTR8fGNocmlzdG1hcyUyMGxpZ2h0c3xlbnwwfHwwfHx8MA%3D%3D&auto=format&fit=crop&w=600&q=60"
          alt="">
      </div>
      <div class="m-5">
        <QuoteForm />
        <h1>Quote form</h1>
        <h3>Insert name here: </h3>
        <h3>Phone number: </h3>
      </div>
    </section>
  </div>
</template>

<script>
import QuoteForm from '../components/QuoteForm.vue';

export default {
  setup() {
    return {};
  },
  components: { QuoteForm }
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

    .img {
      height: 250px;
      max-width: 200px;
      width: 100%;
      object-fit: contain;
      object-position: center;
    }
  }
}
</style>
