<template>
    <div class="home">
        <div>
            <img class="img-fluid" src="@/assets/header.png" alt="">
        </div>
        <div class="content">
            <div class="container">
                <p class="subtitle lead">Hot Game</p>
                <swiper class="mb-3"></swiper>
                <div class="row d-flex flex-row justify-content-between">
                    <div class="d-flex align-items-center col-5">
                        <img class="" src="@/assets/ho_mo.png" alt="">
                        <div class="ken">
                            <div class="ken2"><span>KEN </span><img src="@/assets/ho_vi.png" alt=""><span class="num"> 7</span></div>
                            <div>$<span class="longnum">122121233</span></div>
                        </div>
                    </div>
                    <div class="col-1">
                        <img src="@/assets/line.png" alt="">
                    </div>
                    <div class="col-6 d-flex align-items-center">
                        <div>
                            <img src="@/assets/ho_no@2x.png" alt=""> 
                            <span class="longtext small"> : Dragon Boat Festival holiday!holiday!holiday!holiday! 
                            Dragon Boat Festival</span>
                        </div>
                    </div>
                </div>
                <div class="row py-2">
                    <div class="sidebar col-3 d-flex justify-contnet-center flex-column">
                        <router-link to="#">
                            <img class="rounded mb-3" width="60" src="@/assets/ho_us1@3x.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" width="60" src="@/assets/ho_li2@3x.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" width="60" src="@/assets/ho_sp2@3x.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" width="60" src="@/assets/ho_lo2@3x.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" width="60" src="@/assets/ho_po2@3x.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-5" width="60" src="@/assets/ho_ga2@3x.png" alt="">
                        </router-link>
                        
                    </div>
                    <div class="games col-9">
                        <div class="parent">
                            <router-link to="#">
                                <img class="img-fluid mb-3" src="@/assets/start1.png" alt="">
                            </router-link>
                            <div class="chiled">
                                <div class="maintained">Maintained</div>
                            </div>
                        </div>
                        <router-link to="#">
                            <img class="img-fluid mb-3" width="60" src="@/assets/start2.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="img-fluid mb-3" width="60" src="@/assets/start3.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="img-fluid mb-5" width="60" src="@/assets/start1.png" alt="">
                        </router-link>
                    </div>
                </div>
                <div class="row ">
                    <div class="d-flex col justify-content-between board">
                        <router-link to="#">
                            <img class="rounded mb-3" src="@/assets/ho_ho1.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" src="@/assets/ho_ac2.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" src="@/assets/ho_wa2.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" src="@/assets/ho_co2.png" alt="">
                        </router-link>
                        <router-link to="#">
                            <img class="rounded mb-3" src="@/assets/ho_my2.png" alt="">
                        </router-link>
                    </div>
                </div>
            </div>
            
        </div>
        
    </div>
  
</template>

<script>
import Swiper from "@/components/Swiper.vue"
export default {
    name: "HomeComp",
    components:{
        Swiper
    }
}
</script>

<style>
.content{
    background-color: #0f0f0f;
    padding-top: 20px;
}
.img-fluid {
    width: 100%;
    height: auto;
}
.subtitle{
    color: #edb845;
    font-size: 20px;
}
.ken{
    margin-left: 10px;
    color: #8B8780;
}
.ken .ken2 span{
    font-size: 18px;
}
.ken .ken2 .num{
    font-size: 16px;
}
.longnum{
    color: #edb845;
    font-size: 18px;
}
.longtext{
    word-break: break-all;
    color: #8B8780;
    font-size: 16px; 
}
.parent{
    position: relative;
}
.chiled{
    position: absolute;
    top: 0%;
    left: 0%;
    right: 0%;
    bottom: 0%;
    opacity: 0.8;
    background-color: #0f0f0f;
    z-index: 100;
    display: flex;
    justify-content: center;
    align-items: center;
}
.chiled .maintained{
    opacity: 1;
    color: #8B8780;
    padding: 10px 20px;
    border-radius: 30px;
    background-color: black;
    display: inline-block;
}
.board{
    background-color: #1a1a1a;
    padding-top: 15px;
    border-top-left-radius: 10px;
    border-top-left-radius: 10px;
    position: fixed;
    bottom: 0%;
    left: 0%;
    right: 0%;
    z-index: 1000;
}
.games img{
    height: 100px;
}
</style>