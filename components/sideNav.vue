<template> 
  <div class="sideList">
    <nav>
        <ul>
          <li class="home">
            <nuxt-link to="#">HOME</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">NEWS</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">ABOUT US</nuxt-link>
            <!-- <ul class="aboutList">
              <li>
                <nuxt-link to="#">CONCEPT</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">TOP MESSAGE</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">COMPANY</nuxt-link>
              </li>
              <li>
                <nuxt-link to="#">ACCESS</nuxt-link>
              </li>
            </ul> -->
          </li>
          <li>
            <nuxt-link to="/brands">BRANDS</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">SHOP LIST</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">RECRUIT</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">ACTION</nuxt-link>
          </li>
        </ul>
      </nav>
  </div>
</template>

<script>
export default {
  components: {}
};
</script>

<style>

a{
    color: black;
}

.sideList li{
  margin-bottom: 17px;
}

.sideList .home{
    display: none;
}

.aboutList li{
  margin: 10px;
  font-size: 14px;
  font-weight: bold;
}

  /*スマホ対応*/
@media
 screen and (max-width: 1024px){


     nav{
        margin: 0 auto;
        width: 300px;
     }

     .sideList .home{
         display: inline-block;
     }

   .sideList ul{
        text-align: left;
        margin-left: 50px;
   }

     .sideList li{
        font-size: 13.5px;
        margin: 20px 0;
        display: inline-block;
        top: 50%;
        width: 45%;

     }
 }

</style>