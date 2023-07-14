<script>
// my-component.js
import HeaderComponent from "./components/HeaderComponent.vue";
import CardComponent from "./components/CardComponent.vue";
import MainComponent from "./components/MainComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
export default {
  components :{
    HeaderComponent,
    CardComponent,
    MainComponent,
    FooterComponent,
  },
  data() {
    return {  }
  },
  methods: {}
}
</script>

<template>
<HeaderComponent/>
<CardComponent/>
<MainComponent/>
<FooterComponent/>

</template>

<style lang="scss">
// General

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Fredoka', sans-serif;
   
}

.debug {
    border: 1px dashed black;
     min-height: 20px;
}
.container {
    margin: 0 auto;
    max-width: 1200px;
}
</style>
