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
 <footer>
  <div class="container">
    <div class="row">
      <div class="col">
            <ul>DC COMICS
            <a href=""> <li>  Characters </li> </a>
            <a href=""> <li> Comics </li></a>
           <a href="">  <li>Movies </li></a>
            <a href=""> <li> TV </li></a>
            <a href=""> <li> Games </li></a>
            <a href=""> <li> Videos</li> </a>
            <a href=""> <li> News </li></a>
          </ul>
            <ul>SHOP
            <a href=""> <li>Shop DC </li></a>
             <a href=""> <li>Shop DC Collectibles </li></a> 
            </ul>   
        </div>
        <div class="col-2"></div> 
    </div>
  </div>
  <section>
    <div class="container ">
      <div class="row">
        <div class="col">
          <button>Sign up now!</button>
        </div>
        <div class="col-3">
          <h3>Follow us</h3>
          <img src="../assets/img/footer-facebook.png" alt="">
          <img src="../assets/img/footer-twitter.png" alt="">
          <img src="../assets/img/footer-youtube.png" alt="">
          <img src="../assets/img/footer-pinterest.png" alt="">
          <img src="../assets/img/footer-facebook.png" alt="">
        </div>
      </div>
    </div>
  </section>
 </footer>
</template>

<style lang="scss" scoped>
//  Footer 

footer {
    background-image: url('../assets/img/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size: cover;
    .row {
        display: flex;
        justify-content: space-between; 

        .col {
            color: white;
            padding: 20px;

            ul a {
                text-decoration: none;
                li  {
                    color: #797979;
                        list-style: none;
                        line-height: 10px;
                        margin: 10px;
                }
            }
            
        }
        .col-2 {
            background-image: url('../assets/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            width: 600px;
            height: 500px;
            margin-top: -50px;
        }
    }
  
    section {
        background-color: #303030;
        .row {
            display: flex;

            button {
                padding: 10px;
                border-color: #0282F9;
                    background-color: transparent;
                    color: white;
                    text-transform: uppercase;
            }
            .col-3 {
                display: flex;
                align-items: center;
                h3 {
                    color: #0282F9;
                    text-transform: uppercase;
                }
                img {
                   margin: 5px;
                }
            }
        }
    }
 }
</style>
