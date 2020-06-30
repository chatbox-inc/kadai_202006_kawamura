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
          <li class="aboutus">
            <nuxt-link class="about" to="#">ABOUT US</nuxt-link>
            <div class="aboutList">
                <ul>
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
                </ul>
            </div>
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

nav ul{
    background-color: white;
}

.sideList li{
  margin-bottom: 17px;
}

.sideList .home{
    display: none;
}


/* .about:hover ~ .aboutList {
    display: block;
    position: static;
    opacity: 1;
    transition: all 1s;
} */

.aboutList ul {
    padding-left: 5px;
    margin: 15px 0 25px 0;
}

.aboutList li{
    margin: 10px;
    font-size: 12px;
    letter-spacing: 1px;
}

.aboutus:after{
    width: 95px;
    top: 20px;
}

  /*スマホ対応*/
@media
    screen and (max-width: 1024px){

    .sideList{
        width: 300px;
    }

    .sideList .home{
        display: inline-block;
    }

    .aboutList{
        display: none;
    }

    .sideList ul{
        margin-left:  50px;
        display: flex;
        flex-wrap: wrap;
        width: 250px;
        text-align: left;
    }

    .sideList li{
        font-size: 13.5px;
        margin: 10px 0;
        width: 50%;
    }
 }

</style>