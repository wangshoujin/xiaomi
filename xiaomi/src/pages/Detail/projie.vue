<template>
 <!--商品介绍-->
    <div class="titleView">
        <div class="name">小米Max2 高透保护膜</div>
        <div class="product_desc">高硬度／高透光／轻松粘合</div>
        <div class="priceBox">
            <div class="price">19</div>
        </div>
        <div class="adapt flex-row">
            <div class="tit">适用于</div>
            <div class="alladapt">
                <div class="span">小米Max2</div>
            </div>
        </div>
    </div>
          
</template>

<script>
export default {
  
}
</script>

<style>
/*商品介绍*/
.page-product-view .titleView {
    padding: .32rem;
    text-align: left;
}

.page-product-view .titleView .name {
    font-size: .36rem;
    line-height: .48rem;
    color: rgba(0,0,0,.87);
}

.page-product-view .titleView .product_desc {
    margin-top: .08rem;
    font-size: .24rem;
    color: rgba(0,0,0,.54);
    line-height: .36rem;
}

.page-product-view .titleView .priceBox {
    padding: .16rem 0;
}

.page-product-view .price {
    position: relative;
    display: inline-block;
    margin-left: .25rem;
    font-size: .48rem;
    color: #f56600;
}

.page-product-view .price::before {
    position: absolute;
    top: 0;
    left: -.25rem;
    content: '￥';
    font-size: .32rem;
}

.page-product-view .flex-row {
    display: -webkit-box;
    display: -webkit-flex;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    -webkit-box-pack: center;
    box-pack: center;
    justify-content: space-around;
    -webkit-box-orient: horizontal;
    align-items: center;
}

.page-product-view .titleView .adapt {
    margin-top: .16rem;
    font-size: .24rem;
    color: rgba(0,0,0,.54);
    border-bottom: 1px solid #f4f4f4;
    box-align: start;
    -webkit-box-align: start;
    align-items: flex-start;
    padding-bottom: .32rem;
}

.page-product-view .titleView .adapt .tit {
    width: .96rem;
}

.page-product-view .titleView .adapt .alladapt {
    -webkit-box-flex: 1;
    flex: 1;
}

.page-product-view .titleView .adapt .alladapt .span {
    display: inline-block;
    margin-right: .16rem;
}
</style>


