<template>
  
  <!--商品详情-->
    <div class="descTabsView">
        <ul id="tabs" class="tabs flex-row">
            <li class="tab on">
                <a>商品详情</a>
            </li>
        </ul>

        <div class="tabs-views">
            <div class="views">
                <ul>
                    <li>
                        <div>
                            <div class="img">
                                <img src="../../assets/f2f116d5-9f53-1a76-42ae-89c27c9.jpg">
                            </div>
                        </div>
                    </li>
                </ul>
            </div>
        </div>
    </div>

</template>

<script>
export default {
  
}
</script>

<style>
/*商品详情*/
.page-product-view .descTabsView {
    border-bottom: .16rem solid #efeff0;
}

.page-product-view .descTabsView .tabs {
    background: #fff;
    width: 100%;
    height: .88rem;
    font-size: .24rem;
    color: rgba(0,0,0,.87);
    border-bottom: 1px solid #f4f4f4;
}

.page-product-view .descTabsView .tabs .tab {
    text-align: center;
    border-right: 1px solid #E5E5E5;
    box-flex: 1;
    -webkit-box-flex: 1;
    flex: 1;
    -webkit-flex: 1;
}

.page-product-view .descTabsView .tabs .tab:last-child {
    border-right: 0;
}

.page-product-view .descTabsView .tabs .tab.on {
    color: #f56600;
}

.page-product-view .descTabsView .tabs .tab.on a {
    color: #f56600;
}

.page-product-view .descTabsView .tabs-views {
    width: 100%;
}

.page-product-view .descTabsView .tabs-views img {
    width: 100%;
    height: auto;
}
</style>


