<template>
  <div class="container">
    <div>
      <img src="/src/assets/box.png" class="rounded mx-auto d-block" height="48px">
      <h4 class="text-center">Product Add App</h4>
    </div>
    <hr>
      <appNewProduct></appNewProduct>
    <br>
      <appProgress></appProgress>
    <br>
      <appProducts></appProducts>
  </div>
</template>

<script>
import NewProduct from "./components/NewProduct";
import Products from "./components/Products";
import Progress from "./components/Progress";

  export default {
  components: {
    appNewProduct : NewProduct,
    appProgress : Progress,
    appProducts : Products
  }
  }
</script>

<style>
  body {
    background-color: aliceblue;
    padding-top: 20px;
    padding-bottom: 20px;
  }

  .card{
    margin-right: 5px;
    margin-bottom: 5px;
  }

  .card:last-child{
    margin-right: 0px;
  }

  .col-md-2{
    max-width: 15.666667%!important;
  }

  .product-container{
    margin-left: 15px;
  }

</style>

