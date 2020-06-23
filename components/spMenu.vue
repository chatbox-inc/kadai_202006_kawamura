<template> 
    <div class="menu-wrapper">
        <!-- ハンバーガーメニュー -->
        <input id="hmenu" type="checkbox" />
        <label for="hmenu" class="open"><font-awesome-icon :icon="['fa','bars']" /></label>
        <!-- ハンバーガーメニュー -->
        <div class="spList">
            <!-- ハンバーガーメニュー -->
            <label for="hmenu" class="close">×</label>
            <!-- ハンバーガーメニュー -->
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
                    <li class="online">
                        <a href="#">ONLINE STORE</a>
                    </li>
                </ul>
            </nav>
            <div class="spLink">
                <ul>
                    <li>
                        <a href="#">
                            CONTACT
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            PRIVACY POLICY
                        </a>                    
                    </li>
                    <li>
                        <a href="#">
                            BEWARE OF COUNTERFEITS
                        </a>
                    </li>
                </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  components: {}
};
</script>

<style>

.open,
.close{
    z-index: 10000;
    display: none;
}

input[type="checkbox"] {
    position: absolute;
    left: -50vw;
}

.spList{
    display: none;
}

  /*スマホ対応*/
@media
 screen and (max-width: 1024px){

     .open,
     .close {
         display: block;
     }

     .open{
         position: fixed;
         font-size: 23px;
         top: 22px;
         right: 18px;
     }

     .close {
         position: fixed;
         font-size: 30px;
         top: 22px;
         right: 18px;
     }

     input[type="checkbox"]:checked ~ .spList {
         display:block;
         position: fixed;
         top: 0;
         left: 0;
     }

     .spList{
         font-size:14px;
         padding: 100px 0;
         z-index: 10000;
         position: absolute;
         background-color: white;
         width: 100%;
         height: 100%;
         text-align: center;
         display: none;
     }

     .spList li{
         margin: 13px 0;
     }

     .online{
         font-size: 12px;
         font-weight: 600;
     }

     .spLink{
         padding-top: 20px;
     }

     .spLink ul{
         margin: 0 auto;
         width: 80%;
     }

     .spLink li{
         display: inline-block;
         margin: 0 5px;
         font-size: 12px;
         width: fit-content;
     }

 }



</style>
