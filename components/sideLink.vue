<template>
    <div class="sideLink">
        <div class="link store">
            <a href="#">
                ONLINE STORE
            </a>
        </div>
        <div class="link official">
            <a href="#">
                2⊿_7
            </a>
        </div>
    </div> 
</template>

<script>
export default {
  components: {}
};
</script>

<style>
    .sideLink{
        font-weight: 600;
        margin: 35px 0;
        font-size: 13px;
    }

    .link {
        margin: 10px 0 10px 38px;
    }

/*スマホ対応*/
@media
 screen and (max-width: 1024px){

     .sideLink{
        margin: 0px auto;
        width: 280px;
        text-align: left;
        margin-bottom: 50px;
        /* margin-left: 80px; */
     }

     .link{
         font-size: 11px;
         padding: 0;
         /* margin-left: 80px; */
        display: inline;
        top: 50%;
     }

     .store{
         font-weight: 600;
     }

 }
</style>