<template>
    <div class="cart-index" data-log="购物车">

        <!--购物车头部-->
        <Caheader></Caheader>

        <div class="cart-index-wrap">
            <div>
                <div class="noitems grey">
                    <a>
                        <span>购物车还是空的</span>
                        <router-link tag="em" to="/">去逛逛</router-link>
                    </a>
                </div>
            </div>

            <div class="list-recommend">
                <div>
                    <div class="recommend-title">为你推荐</div>
                    <div class="recommend-list">
                        <ul>
                            <li class="J_linksign-customize"
                            v-for="(item, index) in data" 
                            :key="index">
                                <router-link class="exposure" to="/detail">
                                    <div class="img">
                                        <img class="lazy" :src="item.img_url">
                                    </div>

                                    <div class="recommend-info">
                                        <div class="recommend-name">{{item.name}}</div>
                                        <div class="recommend-price">{{item.price}}</div>
                                        <s class="old"></s>
                                    </div>
                                </router-link>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>

        </div>

        
    </div>
</template>

<script>

import Caheader from './Cart/Caheader'

export default {
    components:{
        Caheader
    },
  data () {
    return {
      data:[
          {img_url:'//i8.mifile.cn/v1/a1/c532a1dd-cd92-8c88-d510-a38c75e16b14.webp?width=720&height=720',
          name:'小米Max 2',
          price:1699},
          {img_url:'//i8.mifile.cn/v1/a1/f444a1cc-1bde-a410-a53f-35b02d183963.webp?width=720&height=720',
          name:'小米5c  64GB 移动版',
          price:1299},
          {img_url:'//i8.mifile.cn/v1/a1/2519ea2f-8d2c-2a43-cf79-550417ce9d30.webp?width=720&height=720',
          name:'小米Max2 高透保护膜',
          price:19},
          {img_url:'//i8.mifile.cn/v1/a1/57ff5e6a-260a-aa9e-6451-7ffb55ef93af.webp?width=720&height=720',
          name:'小米Max 超薄保护套',
          price:29},
          {img_url:'//i8.mifile.cn/v1/a1/138fd453-4cbf-b780-d9b8-bdfa48c8ff41.webp?width=720&height=720',
          name:'小米指环支架',
          price:19},
          {img_url:'//i8.mifile.cn/v1/a1/fc1dfa67-207d-1c71-91cb-c699b60c703a.webp?width=720&height=720',
          name:'红米Note 4X 全网通版',
          price:999},
          {img_url:'//i8.mifile.cn/v1/a1/3a5d0d4a-6ecc-b4ac-8312-1ad57c111ab4.webp?width=720&height=720',
          name:'红米Note 4X高透贴膜',
          price:9.9},
          {img_url:'//i8.mifile.cn/v1/a1/fd015e93-9dd7-e9b2-37ea-c5844831377b.webp?width=720&height=720',
          name:'高透软胶保护套',
          price:19},
          {img_url:'//i8.mifile.cn/v1/a1/21da5518-d5c3-5de7-84b8-afca9446ef93.webp?width=720&height=720',
          name:'小米活塞耳机',
          price:29},
          {img_url:'//i8.mifile.cn/v1/a1/7f47b940-7797-37d9-0a82-9fc08568e277.webp?width=720&height=720',
          name:'小米车载充电器',
          price:49},
          {img_url:'//i8.mifile.cn/v1/a1/808b0701-2d62-73e5-0b16-81da5e8ece7c.webp?width=720&height=720',
          name:'小米米家对讲机',
          price:249},
          {img_url:'//i8.mifile.cn/v1/a1/f093e0a8-e3d8-4fc8-deb7-af25ea3d8663.webp?width=720&height=720',
          name:'米家行车记录仪',
          price:349},
          {img_url:'//i8.mifile.cn/v1/a1/cc91cfe3-c19b-72ef-b420-0d2134061b78.webp?width=720&height=720',
          name:'SanDisk 16GB存储卡',
          price:44.9},
          {img_url:'//i8.mifile.cn/v1/a1/8f6df285-140b-87a1-b1f7-da051fb6ec20.webp?width=720&height=720',
          name:'小米手环2腕带',
          price:19.9},
          {img_url:'//i8.mifile.cn/v1/a1/7b75e0c8-1a65-c389-9c18-22ca7e2eefbc.webp?width=720&height=720',
          name:'小米Note 2',
          price:2799},
          {img_url:'//i8.mifile.cn/v1/a1/3f978d2a-a521-4957-9825-9ea8b436e9ab.webp?width=720&height=720',
          name:'小米Note 2 保护套',
          price:39},
          {img_url:'//i8.mifile.cn/v1/a1/499002db-8847-cd0e-1c1d-088dd9fb7239.webp?width=720&height=720',
          name:'红米4X ',
          price:699},
          {img_url:'//i8.mifile.cn/v1/a1/9b28b9b9-bcc4-8444-db72-399d290884c5.webp?width=720&height=720',
          name:'红米4X 标准高透贴膜',
          price:9.9},
          {img_url:'//i8.mifile.cn/v1/a1/7de4e115-1d01-2b5e-3ec1-76da16f465d5.webp?width=720&height=720',
          name:'高透软胶保护套  ',
          price:19},
          {img_url:'//i8.mifile.cn/v1/a1/e7d9b144-687b-a2d0-69ef-6ed9801077ea.webp?width=720&height=720',
          name:'天鹅绒质感保护壳',
          price:29}
      ]
    }
  }
}
</script>

<style>
/*cart页面*/
.cart-index {
    background: #FFF;
}



/*cart页下面主体*/
.cart-index-wrap {
    padding-bottom: 1.5rem;
}

/*cart页 去逛逛 */
.cart-index-wrap .noitems.grey {
    background: #ebebeb;
}

.cart-index-wrap .noitems.grey>a {
    height: 1.04rem;
}
.cart-index-wrap .noitems>a {
    display: block;
    height: 1.44rem;
    display: flex;
    display: -webkit-flex;
    justify-content: center;
    -webkit-justify-content: center;
    align-items: center;
    -webkit-align-items: center;
    display: box;
    display: -webkit-box;
    
    -webkit-box-align: center;
    
    -webkit-box-pack: center;
    font-size: .24rem;
}

.cart-index-wrap .noitems>a span {
    display: block;
    line-height: .8rem;
    background: url(../assets/cartnull_0de91f1.png) no-repeat 0 center;
    background-size: auto 100%;
    padding: 0 .16rem 0 .96rem;
    color: rgba(0,0,0,.27);
}

.cart-index-wrap .noitems>a em {
    display: block;
    border: 1px solid rgba(0,0,0,.15);
    box-sizing: border-box;
    height: .5rem;
    line-height: .5rem;
    padding: 0 .24rem;
    color: rgba(0,0,0,.87);
}

/*推荐商品*/
.list-recommend {
    background: #fff;
}
.list-recommend .recommend-title {
    height: .8rem;
    line-height: .8rem;
    background: #fff;
    font-size: .3rem;
    padding: 0 .32rem;
}

.list-recommend .recommend-list li {
    float: left;
    width: 50%;
    box-sizing: border-box;
    padding-right: .04rem;
}
.list-recommend .recommend-list li:nth-child(2n) {
    float: right;
    padding-left: .04rem;
    padding-right: 0;
}
.list-recommend .recommend-list li .img {
    position: relative;
}

.list-recommend .recommend-list li .img>img {
    width: 100%;
    height: auto;
    min-height: 3.56rem;
    border: 0;
}

.list-recommend .recommend-list li .recommend-info {
    padding: .18rem .27rem;
}

.list-recommend .recommend-list li .recommend-info .recommend-name {
    font-size: .28rem;
    color: rgba(0,0,0,.87);
    white-space: nowrap;
    overflow: hidden;
}

.list-recommend .recommend-list li .recommend-info .recommend-price {
    font-size: .32rem;
    color: #ff6000;
    margin-top: .1rem;
}

.list-recommend .recommend-list li .recommend-info .recommend-price::before {
    content: "￥";
    font-size: .2rem;
    vertical-align: top;
    margin-right: .05rem;
    font-weight: 400;
    display: inline-block;
    transform: translateY(0.01rem);
    -webkit-transform: translateY(0.01rem);
}
</style>


