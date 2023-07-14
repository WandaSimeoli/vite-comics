<script>
// my-component.js
export default {
  components :{

  },
  data() {
    return { 
    
     }
  },
  props :{
    cardImage: String,
    cardTitle: String,
  },
  methods: {}
}
</script>

<template>
 
  
    <div class="card"> 
      <img :src="cardImage"/> 
      <h3>{{ cardTitle }}</h3>
    </div>
</template>

<style lang="scss" scoped>
  .card {
    width: calc((100% / 6) - 20px);
   margin-top: 30px;

    img {
      width: 80%;
    }

    h3 {
      color: white;
    }
  }
</style>
