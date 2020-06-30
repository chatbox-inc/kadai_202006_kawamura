<template>
  <div class="top-logo">
    <nuxt-link to="/">
      <img src="https://www.a-net.com/wp/wp-content/themes/a-net/images/common/logo.png" alt="A-net">
    </nuxt-link>
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
    width: 98px;
    margin: 38px;
    margin-left: 48px;
  }

  /*スマホ対応*/
@media
screen and (max-width: 1024px){

  .top-logo{
    position: static;
  }

  .top-logo img{
    margin: 10px;
    width: 70px;
    height: auto;
  }
}

</style>