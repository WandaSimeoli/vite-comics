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
 <main>
  <section>
    <div class="container ">
    <div> &#11122; Content goes here &#11120;</div>
  </div>
  </section>
  <section>
    <div class="container">
      <div class="row">
        <div class="col">
          <img src="../assets/img/buy-comics-digital-comics.png" alt="">Digital comics</div>
        <div class="col">
          <img src="../assets/img/buy-comics-merchandise.png" alt="">DC Merchandise</div>
        <div class="col">
          <img src="../assets/img/buy-comics-subscriptions.png" alt="">Subscription</div>
        <div class="col">
          <img src="../assets/img/buy-comics-shop-locator.png" alt="">Comic Shop Locator</div>
        <div class="col">
          <img src="../assets/img/buy-dc-power-visa.svg" alt="">DC Power Visa</div>
      </div>
    </div>
  </section>
 </main>
</template>

<style lang="scss" scoped>
// Main
main {
    section:first-child {
        background-color: black;
        color: white;
        height: 80px;
        font-size: larger;
        font-weight: bold;
        padding: 15px;
    }
    section:nth-child(2) {
        background-color: #0282F9;
        color: white;
        padding: 20px;
        height: 100px;

             .row {
            display: flex;
            justify-content: center;

            .col {
                display: flex;
                align-items: center;
                text-transform: uppercase;
                justify-content: center;
                width: calc(100% / 5);
                img{
                width: 20%;
                padding: 5px;
          }
         }
     }
    }
 }
</style>
