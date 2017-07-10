<template>
  <!--商品详情页顶部悬浮-->
    <div class="fixed-header">
        <div class="left">
            <router-link class="home" to="/">
                <img src="../../assets/back_48bef14.png" class="bgcicon2 ib">
            </router-link>
        </div>

        <div class="right">
            <a>
                <img src="../../assets/share_18c55d7.png" class="search ib">
            </a>
        </div>
    </div>
          
</template>

<script>
export default {
  
}
</script>

<style>
/*商品详情页顶部悬浮*/
.page-product-view {
    background: #FFF;
    max-width: 7.2rem;
    padding-bottom: .86rem;
}
.fixed-header {
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    display: box;
    display: -webkit-box;
    height: .84rem;
    box-align: center;
    -webkit-box-align: center;
    padding: 0 .2rem;
    background-color: rgba(255,255,255,0);
    z-index: 10;
}
.fixed-header .left {
    position: absolute;
    top: .3rem;
    left: .3rem;
}

.fixed-header .left .ib {
    width: .44rem;
    height: .44rem;
}
.fixed-header .right {
    position: absolute;
    top: .3rem;
    right: .3rem;
}

.fixed-header .right .ib {
    width: .44rem;
    height: .44rem;
}
.product-view>img {
    width: 7.2rem;
    height: 7.92rem;
}
</style>


