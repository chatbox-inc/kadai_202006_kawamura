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
      top: 30%;
      position: fixed;
      height: 100%;
  }

  /*スマホ対応*/
@media
 screen and (max-width: 1024px){
     .sideBar {
         position: static;
         top: 50%;
         width: 100%;

     }
 }
</style>

