<template>
    <div class="container">
        <a href="#">
            <div class="topPhoto">
                <img src="https://www.a-net.com/wp/wp-content/uploads/2020/04/main_nya_sp.jpg" alt="nya">
            </div>
        </a>
    </div>
</template>

<style>

.topPhoto{
    padding-top: 100px;
}

.topPhoto img{
    width: 520px;
    height: auto;
}

 /*スマホ対応*/
@media
screen and (max-width: 1024px){

    .topPhoto{
            padding: 0;
    }

    .topPhoto img{
            width: 90%;
            height: auto;
            padding: 70px 0;
    }

    .container img{

    }
}
</style>