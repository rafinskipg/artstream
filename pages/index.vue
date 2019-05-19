<template>
  <section class="container">
    <Header />
    <div class="main">
      
      <h2 class="subtitle">
        The open art platform
      </h2>

      <LastPieces />
      
    </div>
  </section>
</template>

<script>
import Header from '~/components/Header.vue'
import LastPieces from '~/components/LastPieces.vue'

export default {
  components: {
    Header,
    LastPieces
  }
}
</script>

<style >
.container {
  margin: 0 auto;
  min-height: 100vh;
}

.main {
  margin: 0 auto; 
  max-width: 1000px;
  margin-top: 30px;
}


.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
  text-align :center;
}


</style>
