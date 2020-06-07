<template>
  <div>
    <Header />
    <sideBar />
    <main>
      <nuxt />
    </main>
    <footer />
  </div>
</template>

<script>
	import Header from "@/components/header.vue"; //ヘッダーの読み込み
	import SideBar from "@/components/sideBar.vue"; //サイドバーの読み込み
	export default {
		components: {
			Header,
			SideBar
		}
	};
</script>

<style>
</style>
