<template>
  
<!--用户评价-->
    <div class="commentView">
        <a>
            <div class="header-comment flex-row-justify more">
                <div class="left">用户评价(2)</div>
                <div class="right">查看全部评价</div>
            </div>
        </a>
        <a>
            <div class="comment">
                <div class="comment-list">
                    <div class="page">
                        <div class="item">
                            <div class="user">
                                <div class="img">
                                    <img src="../../assets/f790b51a76afd7b41522048fa779d69d.jpg">
                                </div>
                                <div class="name">
                                    <span>1218115622</span>
                                    <span class="date">2017-06-07</span>
                                </div>
                                <div class="zan">
                                    <span>超爱</span>
                                </div>
                            </div>
                            <div class="content">
                                <div class="textbox">发货速度很快，手机没抢到，先把膜买了</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </a>
    </div>
</template>

<script>
export default {
  
}
</script>

<style>
/*用户评价*/
.page-product-view .commentView {
    padding: 0 .32rem .32rem;
    text-align: left;
    border-bottom: .16rem solid #efeff0;
}

.page-product-view .flex-row-justify {
    display: -webkit-box;
    display: -webkit-flex;
    display: flex;
    flex-direction: row;
    flex-wrap: nowrap;
    -webkit-box-pack: justify;
    box-pack: justify;
    justify-content: space-between;
    -webkit-box-orient: horizontal;
    align-items: center;
}

.page-product-view .commentView .header-comment {
    position: relative;
    padding: .32rem 0;
    border-bottom: 1px solid #f4f4f4;
}

.page-product-view .commentView .header-comment .left {
    font-size: .28rem;
    color: rgba(0,0,0,.87);
}

.page-product-view .commentView .header-comment .right {
    margin-right: .4rem;
    font-size: .24rem;
    color: rgba(0,0,0,.72);
}

.comment-list .item {
    border-bottom: 1px solid #ddd;
    padding: .24rem 0 0;
    display: block;
}

.comment-list .item:first-child:last-child {
    border-bottom: 0;
}

.comment-list .user {
    display: box;
    display: -webkit-box;
    box-align: center;
    -webkit-box-align: center;
    box-pack: start;
    -webkit-box-pack: start;
    padding: .16rem 0;
}

.comment-list .user .img {
    margin-right: .24rem;
    width: .8rem;
    min-width: .8rem;
    height: .8rem;
    overflow: hidden;
    box-sizing: border-box;
    border-radius: 100%;
}

.comment-list .user .img img {
    width: 100%;
}

.comment-list .user .name {
    box-flex: 1;
    -webkit-box-flex: 1;
    font-size: .28rem;
    color: rgba(0,0,0,.8);
}

.comment-list .user .name span.date {
    margin-top: .05rem;
    font-size: .2rem;
    color: rgba(0,0,0,.4);
}

.comment-list .user .zan {
    position: relative;
    background: url(../../assets/love_51c21d8.png) no-repeat 0 center;
    background-size: auto 100%;
    width: 1rem;
    height: .34rem;
}

.comment-list .user .zan span {
    position: absolute;
    top: 50%;
    right: .08rem;
    transform: translate3d(0,-50%,0);
    -webkit-transform: translate3d(0,-50%,0);
    color: #ff6b00;
    font-size: .2rem;
}

.comment-list .content>.textbox {
    padding: .12rem 0;
    line-height: .48rem;
    font-size: .28rem;
    color: rgba(0,0,0,.86);
}
</style>


