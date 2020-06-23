<template>
  <div>
    <SpMenu />
    <Header />
    <Logo />
    <main>
      <nuxt />
    </main>
    <SideBar />
    <Footer />
  </div>
</template>
 
<script>
  import SpMenu from "@/components/spMenu.vue";//spメニュー読み込み
  import Header from "@/components/header.vue"; //ヘッダーの読み込み
  import Logo from "@/components/Logo.vue"; //ロゴの読み込み
  import SideBar from "@/components/sideBar.vue"; //サイドバーの読み込み
  import Footer from "@/components/footer.vue";//フッターの読み込み
	export default {
		components: {
      SpMenu,
      Header,
      Logo,
      SideBar,
      Footer
		}
  };
  
</script>

<style>

template{
  font-family: 'Lato','sans-serif';
}

.container{
    margin: 0 0 0 120px;
    text-align: center;
    letter-spacing: 0.8px;
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

     ul{
         padding: 0;
     }
 }

</style>
