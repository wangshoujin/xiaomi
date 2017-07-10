<template>
  
  <!--加入购物车-->
    <div class="product-footer ui-box">
        <a class="br">
            <div class="home icon-home"></div>
            <p class="p">首页</p>
        </a>
        <a>
            <div class="cart icon-gouwuche"></div>
            <p class="p">购物车</p>
        </a>
        <div class="ui-box-flex addCart w50">加入购物车</div>
        <div class="ui-box-flex buyNow w50">立即购买</div>
    </div>

</template>

<<script>
export default {
  
}
</script>

<style>
/*加入购物车*/
.ui-box {
    display: box;
    display: -webkit-box;
    
    -webkit-box-align: center;
   
    -webkit-box-pack: center;
}

.page-product-view .product-footer {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    background-color: #fff;
    padding: 0;
    text-align: center;
    font-size: .32rem;
    z-index: 12;
}

.page-product-view .product-footer>a {
    box-sizing: border-box;
    display: block;
    width: 1.45rem;
    height: .95rem;
    border-top: 1px solid #f4f4f4;
    padding-top: .1rem;
}

.page-product-view .product-footer .br {
    border-right: 1px solid #f4f4f4;
}

.icon-home:before {
    content: "\e606";
}

.page-product-view .product-footer .icon-gouwuche, .page-product-view .product-footer .icon-home {
    font-size: .5rem;
    line-height: .5rem;
}

.icon-gouwuche:before {
    content: "\e605";
}

.page-product-view .product-footer .p {
    font-size: .2rem;
    color: rgba(0,0,0,.72);
}

.page-product-view .w50 {
    width: 2.15rem;
}

.page-product-view .product-footer .addCart {
    -webkit-box-flex: 1;
    flex: 1;
    height: .95rem;
    line-height: .95rem;
    background-color: #f90;
    color: #fff;
}

.page-product-view .product-footer .buyNow {
    -webkit-box-flex: 1;
    flex: 1;
    height: .95rem;
    line-height: .95rem;
    background-color: #f95b07;
    color: #fff;
}
</style>


