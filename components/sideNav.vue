<template> 
  <div>
    <nav>
        <ul>
          <li>
            <nuxt-link to="#">NEWS</nuxt-link>
          </li>
          <li>
            <nuxt-link to="#">ABOUT US</nuxt-link>
          </li>
          <li>
            <nuxt-link to="/brands">BANDS</nuxt-link>
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
　　li {
      list-style-type: none;
    }
</style>