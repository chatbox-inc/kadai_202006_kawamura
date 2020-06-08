<template>
  <div>
    <Header />
    <SideBar />
    <main>
      <nuxt />
    </main>
    <Footer />
  </div>
</template>

<script>
	import Header from "@/components/header.vue"; //ヘッダーの読み込み
  import SideBar from "@/components/sideBar.vue"; //サイドバーの読み込み
  import Footer from "@/components/footer.vue";//フッターの読み込み
	export default {
		components: {
			Header,
      SideBar,
      Footer
		}
	};
</script>

<style>

  li{
    list-style: none;
  }

  a{
    text-decoration: none;
  }
</style>
