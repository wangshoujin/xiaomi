<template>
  
  <!--为你推荐-->
          <div id="recommendWrap" class="recommendWrap">
            <div class="list-recommend">
                <div>
                    <div class="recommend-title">为你推荐</div>
                    <div class="recommend-list">
                        <ul>
                            <li class="J_linksign-customize">
                                <a class="exposure">
                                    <div class="img">
                                        <img class="lazy" src="//i8.mifile.cn/v1/a1/21a20caa-b5e2-5d80-ee4e-d398151644dd.webp?width=720&height=720">
                                    </div>
                                    <div class="recommend-info">
                                        <div class="recommend-name">小米6 高透膜</div>
                                        <div class="recommend-price">29</div>
                                    </div>
                                </a>
                            </li>
                            <li class="J_linksign-customize">
                                <a class="exposure">
                                    <div class="img">
                                        <img class="lazy" src="//i8.mifile.cn/v1/a1/21a20caa-b5e2-5d80-ee4e-d398151644dd.webp?width=720&height=720">
                                    </div>
                                    <div class="recommend-info">
                                        <div class="recommend-name">小米6 高透膜</div>
                                        <div class="recommend-price">29</div>
                                    </div>
                                </a>
                            </li>
                        </ul>
                    </div>
                </div>
            </div>
          </div>

</template>

<script>
export default {
  
}
</script>

<style>
/*为你推荐*/
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

.list-recommend .recommend-list::after, .list-recommend .recommend-list::before {
    content: "";
    height: 0;
    clear: both;
    display: table;
    overflow: hidden;
}

.list-recommend .recommend-list li {
    float: left;
    width: 50%;
    box-sizing: border-box;
    padding-right: .04rem;
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

.list-recommend .recommend-list li:nth-child(2n) {
    float: right;
    padding-left: .04rem;
    padding-right: 0;
}
</style>


