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
</style>

