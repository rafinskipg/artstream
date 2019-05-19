<template>
  <div class="VueToNuxtLogo">
    <div class="Triangle Triangle--two" />
    <div class="Triangle Triangle--one" />
    <div class="Triangle Triangle--three" />
    <div class="Triangle Triangle--four" />
  </div>
</template>

<style>
.VueToNuxtLogo {
  display: inline-block;
  position: relative;
  overflow: hidden;
  height: 50px;
  width: 60px;
}

.Triangle {
  position: absolute;
  top: 0;
  left: 0;
  width: 0;
  height: 0;
}

.Triangle--one {
  left: 10px;
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 50px solid #41b883;
}

.Triangle--two {
  top: 0;
  left: 10px;
  
  border-left: 20px solid transparent;
  border-right: 20px solid transparent;
  border-bottom: 30px solid #3b8070;
}

.Triangle--three {
  top: 20px;
  left: 15px;
  
  border-left: 15px solid transparent;
  border-right: 15px solid transparent;
  border-bottom: 10px solid #35495e;
}

.Triangle--four {
  top: 20px;
  left: 25px;
  border-left: 5px solid transparent;
  border-right: 5px solid transparent;
  border-bottom: 10px solid #fff;
}

</style>
