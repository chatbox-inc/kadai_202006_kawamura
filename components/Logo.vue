<template>
  <div class="top-logo">
    <a href="https://www.a-net.com/">  
      <img src="https://www.a-net.com/wp/wp-content/themes/a-net/images/common/logo.png" alt="A-net">
    </a>
  </div>
</template>
<script>
export default {
  components: {}
};
</script>

<style>
  .top-logo{
    margin: 0;
    position: fixed;
  }
  .top-logo img{
    width: 120px;
  }

  /*スマホ対応*/
@media
 screen and (max-width: 1024px){

   .top-logo{
     position: static;
   }
 }

</style>