<template>
 <!--已选-->
    <div class="attrsQaView J_linksign-customize">
        <div class="div more">
            <p class="has">已选</p>
            <div class="productInfo">小米Max2 高透保护膜 高透 x1</div>
        </div>
        <div class="div more" style="display:none">
            <p class="has">请选择版本</p>
        </div>
    </div>
          
</template>

<script>
export default {
  
}
</script>

<style>
/*已选*/
.page-product-view .attrsQaView {
    padding: 0 .32rem .32rem;
    text-align: left;
    border-bottom: .16rem solid #efeff0;
}

.page-product-view .div {
    position: relative;
}

.page-product-view .attrsQaView .has {
    font-size: .24rem;
    color: rgba(0,0,0,.54);
}

.page-product-view .attrsQaView .productInfo {
    margin-top: .1rem;
    font-size: .24rem;
    color: rgba(0,0,0,.87);
    line-height: .4rem;
    padding-right: .2rem;
}

.page-product-view .more:after {
    content: '\0020';
    display: block;
    width: .14rem;
    height: .14rem;
    border-top: 1px solid #ddd;
    border-right: 1px solid #ddd;
    position: absolute;
    top: 50%;
    right: 0rem;
    margin-top: -.07rem;
    -webkit-transition: .2s ease;
    -webkit-transition-delay: 0s;
    -moz-transition: .2s ease;
    -o-transition: .2s ease;
    transition: .2s ease;
    -webkit-transform: rotate(45deg);
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -o-transform: rotate(45deg);
    transform: rotate(45deg);
}
</style>


