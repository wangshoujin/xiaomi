<template>
  <!--购物车头部-->
    <div class="header">
        <router-link class="home" to="/">
            <img src="../../assets/icon_back_n.png" class="ib">
        </router-link>
        <span>购物车</span>
        <div class="right">
            <a>
                <div class="icon icon-search"></div>
            </a>
        </div>
    </div>
          
</template>

<<script>
export default {
  
}
</script>

<style>
/*cart页面header*/
.header { 
    height: .84rem;
    padding: 0 .2rem;
    background: #f2f2f2;
    position: relative;
    border-bottom: 1px solid #eee;
}

.header .home {
    display: inline-block;
   
    width: .44rem;
    height: .44rem;
    margin-top:.2rem;
}
.header .home .ib{
    width:100%;
    height:100%;
}
.header span{
    display: inline-block;
    height:.44rem;
    font-size:.3rem;
    color:#666;
    margin-left:2.6rem;
    
}
.header .right{
    float:right;
    margin-top:.2rem;
}
.header .right a {
    display: inline-block;
    margin-left: .2rem;
    width: .44rem;
    height: .44rem;
    font-size: .44rem;
}

.header .right .icon {
    color: #999;
}
.icon-search:before {
    content: "\e632";
}
</style>


