<template>
  <div class="home">
    <!-- banner -->
    <el-carousel class="bannerHeight">
      <el-carousel-item key=1>
        <img class="images-con" src="../assets/home1.jpg">
      </el-carousel-item>
      <el-carousel-item key=2>
        <img class="images-con" src="../assets/home2.jpg">
      </el-carousel-item>
      <el-carousel-item key=3>
        <img class="images-con" src="../assets/home3.jpg">
      </el-carousel-item>
      <el-carousel-item key=4>
        <img class="images-con" src="../assets/home4.jpg">
      </el-carousel-item>
    </el-carousel>
    <!-- /ends banner -->
    <!-- HomeArticle -->
    <div class="box-flex flex-direction-column margin-top-2">
      <!-- article1 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/homeArticle1.png">
          </div>
          <div class="box-flex flex-1 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">Vue应用及组件分享</span>
            </a>
            <span class="contentFont">Vue应用及组件分享</span>
          </div>
        </div>
      </div>
      <!-- /ends article1 -->
      <!-- article2 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="box-flex flex-1 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">实现</span>
            </a>
            <span class="contentFont">实现</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/homeArticle2.png">
          </div>
        </div>
      </div>
      <!-- /ends article2 -->
      <!-- article3 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/homeArticle3.jpg">
          </div>
          <div class="box-flex flex-1 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">Vue应用及组件分享</span>
            </a>
            <span class="contentFont">Vue应用及组件分享</span>
          </div>
        </div>
      </div>
      <!-- /ends article3 -->
      <!-- article4 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="box-flex flex-1 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">实现</span>
            </a>
            <span class="contentFont">实现</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/homeArticle4.jpg">
          </div>
        </div>
      </div>
      <!-- /ends article4 -->
      <!-- article5 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/homeArticle5.png">
          </div>
          <div class="box-flex flex-1 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">Vue应用及组件分享</span>
            </a>
            <span class="contentFont">Vue应用及组件分享</span>
          </div>
        </div>
      </div>
      <!-- /ends article5 -->
    </div>
    <!-- /ends HomeArticle -->
    <!-- My Work -->
    <div
      class="box-flex width-80 margin-auto margin-top-2 padding-top-5 padding-bottom-3 text-align-center flex-justify-center flex-items-center">
      <div class="line-height-30 font-size-26 lineThrou">My Work</div>
    </div>
    <div
      class="box-flex width-100 margin-auto text-align-center flex-direction-column flex-wrap flex-justify-center flex-items-center flex-content-space-around">
      <div class="box-flex flex-direction-row margin-top-2" style="height:60vh">
        <div class="flex-2 overflow-hide flex-direction-column">
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/pi2.jpg">
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/pic.jpg">
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/bg1.jpg">
          </div>
        </div>
        <div class="flex-4 flex-direction-column">
          <div class="flex-4 overflow-hide" style="height:40vh">
            <img class="images-height100 imgpic" src="../assets/bg2.jpg">
          </div>
          <div class="box-flex flex-2 overflow-hide flex-direction-row flex-justify-flex-start flex-items-flex-start"
               style="height:20vh">
            <div class="flex-1" style="width:50%;height:20vh">
              <img class="images-height100 imgpic" src="../assets/bg3.jpg">
            </div>
            <div class="flex-1" style="width:50%;height:20vh">
              <img class="images-height100 imgpic" src="../assets/pi2.jpg">
            </div>
          </div>
        </div>
        <div class="flex-2 overflow-hide flex-direction-column">
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/pic.jpg">
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/bg1.jpg">
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/pi1.jpg">
          </div>
        </div>
      </div>
    </div>
    <!-- /ends My Work -->
    <!-- Personal Profile -->
    <div
      class="bg-efeff4 box-flex width-100 margin-auto margin-top-2 padding-top-5 padding-bottom-5 text-align-center flex-justify-center flex-items-center">
      <div class="line-height-30 font-size-26 lineThrou">Personal Profile</div>
    </div>
    <div
      class="bg-efeff4 box-flex width-100 text-align-center margin-auto padding-all padding-bottom-5 perenContent flex-justify-center flex-items-center">
      <div class="box-flex flex-1 flex-direction-column flex-justify-center flex-items-center">
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-happy-outline font-size-16"></span>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">zzm</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-email-outline font-size-16"></span>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">zhaozimu2011@hotmail.com</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-telephone-outline font-size-16"></span>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">18518980722</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-list-outline font-size-16"></span>
          </div>
          <div class="box-flex flex-3 padding-left-3 text-align-left">
            <p>90后，技术宅，前端狂热爱好者，设计爱好者，动漫迷，游戏爱好者，目前所在地 上海浦东<br/>
              技术栈 ：web前端，UI设计，nodejs express mongodb ，react ，vue ，angularjs Ionic||angularjs bootstrap ，ReactNative，php Thinkphp mysql<br/>
              GitHub个人主页地址： https://github.com/liuyahuiZ<br/>
              站酷个人主页地址：http://paoying.zcool.com.cn<br/>
            </p>
          </div>
        </div>
      </div>
      <div class="box-flex flex-1 flex-direction-column flex-justify-center flex-items-center">
        <div class="imground">
          <img class="imground" src="../assets/headImg.jpg">
        </div>
      </div>
    </div>
    <!-- /ends Personal Profile -->
    <div class="box-flex height-200 bg-333 flex-direction-column flex-justify-center flex-items-center">
      <div class="line-height-30 tirtleFont textclolor-black-low">
        © 2017 All rights reserved. Development by ZIMOON
      </div>
      <div class="line-height-30 iconFont textclolor-white ">Projects made with </div>
      <my-link></my-link>
    </div>
  </div>
</template>
<script>
  import myLink from '@/components/mylink'
  export default {
    components: {
      myLink
    }
  }
</script>
<style>
  .box-flex .imgpic {
    transition: .7s all;
    opacity: 0.8;
  }

  .box-flex .imgpic:hover {
    opacity: 1;
    box-shadow: 1px 1px 20px #333;
    transform: scale(1.1, 1.1);
    cursor: pointer;
  }

  .lineThrou {
    transition: .8s all;
  }

  .lineThrou:hover {
    text-decoration: line-through;
    cursor: pointer
  }

</style>
