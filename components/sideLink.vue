<template>
    <div class="sideLink">
        <ul>
            <li class="link store">
                <a href="#">
                    ONLINE STORE
                </a>
            </li>
            <li class="link official">
                <a href="#">
                    2⊿_7
                </a>
            </li>
        </ul>
    </div> 
</template>

<script>
export default {
    components: {}
};
</script>

<style>
    .sideLink{
        font-weight: 600;
        margin: 35px 0;
        font-size: 13px;
    }

    .sideLink li{
        margin-left: 0;
    }

    .link {
        margin: 10px 0 10px 38px;
    }

/*スマホ対応*/
@media
 screen and (max-width: 1024px){

    .sideLink{
        margin: 0 0 50px 0;
    }

    .sideLink ul{
        display: flex;
        width: 250px;
        margin: 0 0 0 50px;
        text-align: left;
    }

    .sideLink li{
        width: 50%;
    }

    .link{
        font-size: 11px;
        padding: 0;
        display: inline;
        top: 50%;
    }

    .store{
        font-weight: 600;
    }

}
</style>