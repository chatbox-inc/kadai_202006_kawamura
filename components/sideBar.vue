<template>
    <div class="sideBar">
        <sideNav />
        <sideLink />
    </div>
</template>

<script>
import SideNav from"@/components/sideNav";
import SideLink from"@/components/sideLink";
export default {
    components: {
        SideNav,
        SideLink
    }
};
</script>

<style>

   .sideBar {
      top: 32%;
      position: fixed;
      height: 100%;
      margin-left: 10px;
      font-size: 14.5px;
      letter-spacing: 2px;
  }

  /*スマホ対応*/
@media
 screen and (max-width: 1024px){
     .sideBar {
         position: static;
         top: 50%;
         width: 300px;

     }
 }
</style>

