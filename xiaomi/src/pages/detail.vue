<template>
  <div class="page-product-view" data-log="商品详情">
      <div class="product-view">

          <!--商品详情页顶部悬浮-->
          <deheader></deheader>

          <img src="//i8.mifile.cn/v1/a1/2d538f37-8157-8c08-1ab3-0c36a0481464.webp">
          <div id="slider" class="slider"></div>

          <!--商品介绍-->
          <deprojie></deprojie>

          <!--已选-->
          <deyixuan></deyixuan>
          
          <!--地址-->
          <deaddress></deaddress>

          <!--用户评价-->
          <depingjia></depingjia>

          <!--商品详情-->
          <dexiangqing></dexiangqing>

          <!--为你推荐-->
          <detuijian></detuijian>

          <!--加入购物车-->
          <decartt></decartt>

      </div>
  </div>
</template>

<script>
import deheader from './Detail/deHeader'
import deprojie from './Detail/projie'
import deyixuan from './Detail/yixuan'
import deaddress from './Detail/address'
import depingjia from './Detail/pingjia'
import dexiangqing from './Detail/xiangqing'
import detuijian from './Detail/tuijian'
import decartt from './Detail/cartt'

export default {
  components:{
        deheader,
        deprojie,
        deyixuan,
        deaddress,
        depingjia,
        dexiangqing,
        detuijian,
        decartt
    }
}
</script>

<style>


</style>


