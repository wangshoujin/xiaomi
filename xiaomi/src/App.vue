<template>
  <div id="app">
   
    <router-view></router-view>
    
    <ul class="footer">
      
        <router-link tag="li" to="/">
          <div class="nav" @click="flag=[0, 1, 1, 1]">
            <div class="ispr" 
            :class="{true:'ih-current',false:'ih'}[flag[0]==0]"></div>

            <p :class="{true:'curColor',false:''}[flag[0]==0]">首页</p>
          </div>
        </router-link>
      
        <router-link tag="li" to="/market">
          <div class="nav" @click="flag=[1, 0, 1, 1]">
            <div class="ispr"
            :class="{true:'ic-current',false:'ic'}[flag[1]==0]"></div>

            <p :class="{true:'curColor',false:''}[flag[1]==0]">分类</p>
          </div>
        </router-link>
      
        <router-link tag="li" to="/cart2">
          <div class="nav"  @click="flag=[1, 1, 0, 1]">
            <div class="ispr" 
            :class="{true:'is-current',false:'is'}[flag[2]==0]"></div>

            <p :class="{true:'curColor',false:''}[flag[2]==0]">购物车</p>
          </div>
        </router-link>
      
        <router-link tag="li" to="/mine">
          <div class="nav" 
          @click="flag=[1, 1, 1, 0]">
            <div class="ispr" 
             :class="{true:'if-current',false:'if'}[flag[3]==0]"></div>

            <p :class="{true:'curColor',false:''}[flag[3]==0]">我的</p>
          </div>
        </router-link>
      
    </ul>
    
  </div>
</template>

<script>
import './assets/reset.css'
export default {
  name: 'app',
  data:function(){
    return {
      flag:[0,1,1,1]
    }  
  }
}

</script>

<style>

.footer{
  list-style: none;
  display: flex;
  z-index:10;
  align-items: center;
  position: fixed;
  background: #fff;
  border-top:1px solid #e0e0e0;
  bottom:0;
  left:0;
  right:0;
}
.footer li{
  width:25%;
  text-align: center;
  padding:.12rem 0;
}
.footer .nav .ispr{
  width:.4rem;
  height:.4rem;
  background-image: url(assets/foot.png);
  background-size:.4rem 3.2rem;
  overflow:hidden;
  margin:0 auto .08rem;
}
.footer .nav .ispr.ih{
  background-position-y: -2.8rem;
}
.footer .nav .ispr.ic{
  background-position-y: -.4rem;
}
.footer .nav .ispr.is{
  background-position-y: -1.2rem;
}
.footer .nav .ispr.if{
  background-position-y: -2rem;
}
.footer .nav .ispr.ih-current{
  background-position-y: -2.4rem;
}
.footer .nav .ispr.ic-current{
  background-position-y: 0rem;
}
.footer .nav .ispr.is-current{
  background-position-y: -.8rem;
}
.footer .nav .ispr.if-current{
  background-position-y: -1.6rem;
}
.footer .nav p{
  font-size:.22rem;
  line-height:.8;
  color:#999;
}
.footer .nav .curColor{
  color:#FF5722;
}
</style>
