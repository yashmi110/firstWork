<template>
  <div id="app">
   <!-- <img src="./assets/logo.png">-->
    <header>
      <h1>
          {{title}}
      </h1>
    </header>
   <body>
  

     <div class="row">
  <div class="column1" style="background-color:#76D7C4;">
    <h2>Chicken Burger</h2>
    <img src="./assets/burger1.png" width="200" height="150">
  </div>
  <div class="column2" style="background-color:#ECF0F1;">

    <p>“Tasty, delicious, and has me craving more on the first bite.” to “Juicy, mouthwatering, tasty, and everything you’d ever want to savor.”</p>
    <h6 class="price">Rs.650/= to Rs.1250/=</h6>
  </div>
</div>

<div class="row">
  <div class="column1" style="background-color:#F7DC6F;">
    <h2>Crisps</h2>
    <img src="./assets/crisps.png">
  </div>
  <div class="column2" style="background-color:#ECF0F1 ;">
   
    <p>"A vampire victim. I'd never seen a lone kill. They were like potato chips; once a vamp tasted them, he couldn't stop at just one."</p>
    <h6 class="price">Rs.150/= to Rs.250/=</h6>
  </div>
</div>

<div class="row">
  <div class="column1" style="background-color:#27AE60;">
    <h2>Salad</h2>
    <img src="./assets/salad.jpg" width="150" height="150">
  </div>
  <div class="column2" style="background-color:#ECF0F1 ;">
    
    <p>“Salad is never more appetizing than when served in a large wooden bowl.”</p>
    <h6 class="price">Rs.350/= to Rs.600/=</h6>
  </div>
</div>

<div class="row">
  <div class="column1" style="background-color:#D4AC0D;">
    <h2>Thosei</h2>
    <img src="./assets/Those.png" width="150" height="150">
  </div>
  <div class="column2" style="background-color:#ECF0F1 ;">
    
    <p>"If you don't love south indian cuisine, you're either an alien or your taste buds are spoiled"</p>
  <h6 class="price">Rs.50/= to Rs.250/=</h6>
</div>
</div>


<div class="row">
  <div class="column1" style="background-color:#E59866;">
    <h2>Pizza</h2>
    <img src="./assets/pizza1.png" width="150" height="150">
  </div>
  <div class="column2" style="background-color:#ECF0F1 ;">
    
    <p>"Pizza is not a 'trend' it's a way of life"</p>
    <h6 class="price">Rs.750/= to Rs.2150/=</h6>
  </div>
</div>


   </body>
  </div>
</template>



<script>
export default {
  name: 'app',
  data () {
    return {
     title:'VIJAY RESTURANT - MENU LIST'
    }
  }
}
</script>

<style scoped>
h6{
font-family: Times New Roman;
color: red;
text-align: right;
}
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  background-color: #EBDEF0;
}

header{
    background-color: #EBDEF0;
    padding: 10px;
     
}

h1{
    color: #222;
    text-align: center;
    font-family:Copperplate;
}

 *{
  box-sizing: border-box;
}

.row{
  display: flex;
   padding: 10px;
}



/* Create two equal columns that sits next to each other */
.column1 {
  flex: 30%;
  padding: 10px;
  height: 250px; /* Should be removed. Only for demonstration */
  font-family:Courier New;

}
.column2 {
  flex: 80%;
  padding: 10px;
  height: 250px; /* Should be removed. Only for demonstration */
  font-family:Garamond;
  font-size: 35px;
}
</style>
