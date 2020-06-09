<template>
    <div class="sideLink">
        <div class="link">
            <a href="#">
                ONLINE STORE
            </a>
        </div>
        <div class="link">
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
    .link {
        margin: 10px 0 10px 38px;
    }

/*スマホ対応*/
@media
 screen and (max-width: 1024px){

     .sideLink{
         display: flex;
         justify-content: center;
     }

     .link{
         margin: 30px;
     }

 }
</style>