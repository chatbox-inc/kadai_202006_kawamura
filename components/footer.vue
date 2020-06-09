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
                        メールマガジンサービス変更のお知らせ
                    </a>
                </li>
                <li>
                    <a href="#">
                        A-net Membershipのご案内 
                    </a>
                </li>
                <li>
                    <a href="#">
                        旧ポイントカードに関して
                    </a>
                </li>
            </ul>
        </div>
        <div class="copyright">
            <p>Copyright © 2020 A-net inc. All Rights Reserved.</p>
        </div>
    </footer>
    
</template>

<script>
export default {
  components: {}
};
</script>

<style>

footer li{
    display: inline;
    margin: 0 15px;
}

.footerRight{
    text-align: right;
}

   /*スマホ対応*/
@media
 screen and (max-width: 1024px){
     footer{
         font-size: 12px;
         text-align: center;
     }

     ul{
         padding: 0;
     }

     footer li{
         margin: 0 8px;
     }

     .footerRight{
         text-align: center;
         margin: 30px 0;
     }

     .footerRight li{
         display: block;
     }
 }


</style>