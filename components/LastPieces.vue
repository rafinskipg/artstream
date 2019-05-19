<template>
  <div class="last-pieces">
    <h2>Last Pieces of Art</h2>
    <div class="pieces">
      <div class="piece" v-for="piece in pieces">
        <div class="img"></div>
        <div class="info">
          <div class="price">100€</div>
          <div class="author">Author</div>
        </div>
      </div>
    </div>
   
  </div>
</template>

<script>


export default {
  data() {
    return {
      pieces : [1,2,3,4]
    }
  }
}
</script>

<style>
.pieces {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-between;
  align-items: center;
}

h2 {
  margin-bottom: 30px;
}

.img {
  width: 200px;
  height: 200px;
  background: black;
  margin-bottom: 15px;
}

.info {
  text-align: center;
}

.piece {
  margin-bottom: 30px;
}
</style>
