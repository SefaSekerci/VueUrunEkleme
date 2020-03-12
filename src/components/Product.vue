<template>
  <div class="col-md-2 card">
      <slot></slot>
  </div>

</template>

<script>
export default {
    
};
</script>

<style  scoped>
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