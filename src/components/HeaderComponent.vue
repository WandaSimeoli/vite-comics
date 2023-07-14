<script>
// my-component.js
export default {
  components :{

  },
  data() {
    return {  }
  },
  methods: {}
}
</script>

<template>
 <header>
  <div class="container">
  <div class="row  ">
    <div class="col ">
      <img src="../assets/img/dc-logo.png" alt="">
    </div>
    <div class="col ">
      <nav>
        <ul> <a href=""><li>Characters</li></a>
        <a href=""><li>Comics</li></a>
        <a href=""><li>Movies</li></a>
        <a href=""><li>TV</li></a>
        <a href=""><li>Games</li></a>
        <a href=""><li>Collectibles</li></a>
        <a href=""><li>Videos</li></a>
        <a href=""><li>Fans</li></a>
        <a href=""><li>news</li></a>
        <a href=""><li>shop</li></a>
       </ul>
      </nav>
    </div>
  </div>
</div>
 </header>
</template>

<style lang="scss" scoped>
// Header 
header {

padding: 20px;

.row {
    display: flex;
    justify-content: space-between;

     ul a li {
       list-style: none;
       display: inline-block; 
       padding: 15px;
       text-transform: uppercase;
       text-decoration: none;
       color: black;
     
    }
}
}
</style>
