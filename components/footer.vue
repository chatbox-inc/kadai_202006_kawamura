<template>
    <footer>
        <div class="footerLeft">
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
        <div class="footerRight">
            <ul>
                <li>
                    <a href="#">
                        <font-awesome-icon :icon="['fa','envelope']" />
                        メールマガジンサービス変更のお知らせ
                    </a>
                </li>
                <li>
                    <a href="#">
                        <font-awesome-icon :icon="['fa','user']" />
                        A-net Membershipのご案内 
                    </a>
                </li>
                <li>
                    <a href="#">
                        <font-awesome-icon :icon="['fa','credit-card']" />
                        旧ポイントカードに関して
                    </a>
                </li>
            </ul>
            <div class="copyright">
                <p>Copyright © 2020 A-net inc. All Rights Reserved.</p>
            </div>
        </div>
    </footer>
    
</template>

<script>
export default {
  components: {}
};
</script>

<style>

footer{
    position: relative;
    width: 100%;
    line-height: 8px;
    font-size: 11px;
}

.footerLeft ul{
    position: absolute;
    top: 10px;
}

footer li{
    display: inline-block;
    margin: 0 15px;
}

.footerRight{
    text-align: right;
}

.copyright{
    margin: 0 15px;
    /* width: fit-content; */
}

   /*スマホ対応*/
@media
 screen and (max-width: 1024px){
     footer{
         line-height: 25px;
         font-size: 12px;
         text-align: center;
     }

     .footerLeft ul{
    position: static;
    }

     footer li{
         margin: 0 8px;
     }

     .footerRight{
         text-align: center;
         margin: 30px 0;
         font-size: 11px;
     }

     .footerRight li{
         display: block;
     }
 }


</style>