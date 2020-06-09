<template>
  <div>
    <Header />
    <main>
      <nuxt />
    </main>
    <SideBar />
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

.container{
    margin: 0 0 0 200px;
    text-align: center;
}

  li{
    list-style: none;
  }

  a{
    text-decoration: none;
  }

   /*スマホ対応*/
@media
 screen and (max-width: 1024px){
     .container{
         margin: 0 auto;
     }
 }

</style>
