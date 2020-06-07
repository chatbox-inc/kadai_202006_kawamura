<template>
    <div class="sideBar">
        <sideNav />
    </div>
</template>

<script>
import SideNav from"@/components/sideNav";
export default {
    components: {
        SideNav
    }
};
</script>

<style>
   .sideBar {
      top: 50%;
      position: fixed;
      height: 100%;
  }
</style>

