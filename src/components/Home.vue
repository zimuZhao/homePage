<template>
  <div class="home">
    <!-- banner -->
    <el-carousel class="bannerHeight">
      <el-carousel-item key=1>
        <img class="images-con" src="../assets/home1.jpg"/>
      </el-carousel-item>
      <el-carousel-item key=2>
        <img class="images-con" src="../assets/home2.jpg"/>
      </el-carousel-item>
      <el-carousel-item key=3>
        <img class="images-con" src="../assets/home3.jpg"/>
      </el-carousel-item>
      <el-carousel-item key=4>
        <img class="images-con" src="../assets/home4.jpg"/>
      </el-carousel-item>
    </el-carousel>
    <!-- /ends banner -->
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
            <a href="http://zimu4show.cn/InvitationLetter/index.html" target="_blank">
              <img class="images-height100 imgpic" src="../assets/project2.jpg"/>
            </a>
          </div>
          <div style="height:20vh">
            <a href="http://www.cloudpioneer.com.cn/" target="_blank">
              <img class="images-height100 imgpic" src="../assets/project5.jpg"/>
            </a>
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/project3.jpg"/>
          </div>
        </div>
        <div class="flex-4 flex-direction-column">
          <div class="flex-4 overflow-hide" style="height:40vh">
            <a href="http://zimu4show.cn/showcase/player.html" target="_blank">
              <img class="images-height100 imgpic" src="../assets/project1.jpg"/>
            </a>
          </div>
          <div class="box-flex flex-2 overflow-hide flex-direction-row flex-justify-flex-start flex-items-flex-start"
               style="height:20vh">
            <div class="flex-1" style="width:50%;height:20vh">
              <a href="http://zimu4show.cn/BazhuaWIFI/index.html" target="_blank">
                <img class="images-height100 imgpic" src="../assets/project4.png"/>
              </a>
            </div>
            <div class="flex-1" style="width:50%;height:20vh">
              <a href="http://zimu4show.cn/touch-unlock.html" target="_blank">
                <img class="images-height100 imgpic" src="../assets/project7.jpg"/>
              </a>
            </div>
          </div>
        </div>
        <div class="flex-2 overflow-hide flex-direction-column">
          <div style="height:20vh">
            <a href="http://zimu4show.cn/snowDay/HIT.html" target="_blank">
              <img class="images-height100 imgpic" src="../assets/project6.jpg"/>
            </a>
          </div>
          <div style="height:20vh">
            <a href="http://zimu4show.cn/next-day/next-day.html" target="_blank">
              <img class="images-height100 imgpic" src="../assets/project8.jpg"/>
            </a>
          </div>
          <div style="height:20vh">
            <img class="images-height100 imgpic" src="../assets/project1.jpg"/>
          </div>
        </div>
      </div>
    </div>
    <!-- /ends My Work -->
    <!--projectList -->
    <div class="box-flex flex-direction-column margin-top-2">
      <!-- 会议会展宣传 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project1.jpg"/>
          </div>
          <div class="box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/showcase/player.html" target="_blank">
              <span class="tirtleFont lineThrou">会议会展宣传</span>
            </a>
            <span class="contentFont">
              公司参与多彩贵州网2016年5月7日举办的产品推介会所展示的H5。<br>
              钥匙还在身上，回家的路并不遥远...
            </span>
          </div>
        </div>
      </div>
      <!-- /ends 会议会展宣传 -->
      <!-- 数据解读 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="text-right box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/InvitationLetter/index.html" target="_blank">
              <span class="tirtleFont lineThrou">数据解读</span>
            </a>
            <span class="contentFont">移动端分析数据H5展示页</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project2.jpg"/>
          </div>
        </div>
      </div>
      <!-- /ends 数据解读 -->
      <!-- 民生银行抽奖 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project3.jpg"/>
          </div>
          <div class="box-flex flex-2 padding-all flex-direction-column">
            <a href="#">
              <span class="tirtleFont lineThrou">2016民生银行刮卡领奖活动</span>
            </a>
            <span class="contentFont">内嵌于微信公众号的活动页</span>
          </div>
        </div>
      </div>
      <!-- /ends 民生银行抽奖 -->
      <!-- 八爪WIFI宣传 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="text-right box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/BazhuaWIFI/index.html" target="_blank">
              <span class="tirtleFont lineThrou">八爪WIFI宣传</span>
            </a>
            <span class="contentFont">产品宣传网站</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project4.png"/>
          </div>
        </div>
      </div>
      <!-- /ends 八爪WIFI宣传 -->
      <!-- 公司官网 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project5.jpg"/>
          </div>
          <div class="box-flex flex-2 padding-all flex-direction-column">
            <a href="http://www.cloudpioneer.com.cn/" target="_blank">
              <span class="tirtleFont lineThrou">Cloudpioneer贵州耕云科技官方网站</span>
            </a>
            <span class="contentFont">公司官网</span>
          </div>
        </div>
      </div>
      <!-- /ends 公司官网 -->
      <!-- 八爪WIFI宣传 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="text-right box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/snowDay/HIT.html" target="_blank">
              <span class="tirtleFont lineThrou">工大雪夜</span>
            </a>
            <span class="contentFont">Three.js绘制webGL初试</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project6.jpg"/>
          </div>
        </div>
      </div>
      <!-- /ends 八爪WIFI宣传 -->
      <!-- 手势解锁 left -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project7.jpg"/>
          </div>
          <div class="box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/touch-unlock.html" target="_blank">
              <span class="tirtleFont lineThrou">手势解锁</span>
            </a>
            <span class="contentFont">存储canvas绘制路径以备比对</span>
          </div>
        </div>
      </div>
      <!-- /ends 手势解锁 -->
      <!-- 计算明天 right -->
      <div class="box-flex width-80 margin-auto">
        <div class="box-flex width-100">
          <div class="text-right box-flex flex-2 padding-all flex-direction-column">
            <a href="http://zimu4show.cn/next-day/next-day.html" target="_blank">
              <span class="tirtleFont lineThrou">计算明天</span>
            </a>
            <span class="contentFont">HIT小作业</span>
          </div>
          <div class="flex-1">
            <img class="images-con imgpic" src="../assets/project8.jpg"/>
          </div>
        </div>
      </div>
      <!-- /ends 明天计算 -->
    </div>
    <!-- /ends projectList -->
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
            <span class="ion-happy-outline font-size-16"/>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">zzm</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-email-outline font-size-16"/>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">zhaozimu2011@hotmail.com</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-telephone-outline font-size-16"/>
          </div>
          <div class="box-flex flex-3 height-40 line-height-40 padding-left-3">18518980722</div>
        </div>
        <div class="box-flex width-100 flex-direction-row">
          <div class="box-flex flex-1 flex-justify-flex-end height-40 line-height-40">
            <span class="ion-ios-list-outline font-size-16"/>
          </div>
          <div class="box-flex flex-3 padding-left-3 text-align-left">
            <p>
              90后，技术宅，前端狂热爱好者<br/>
              坐标： 北京<br/>
              GitHub地址： https://github.com/zimuZhao<br/>
            </p>
          </div>
        </div>
      </div>
      <div class="box-flex flex-1 flex-direction-column flex-justify-center flex-items-center">
        <div class="imground">
          <img class="imground" src="../assets/headImg.jpg"/>
        </div>
      </div>
    </div>
    <!-- /ends Personal Profile -->
    <div class="box-flex height-200 bg-333 flex-direction-column flex-justify-center flex-items-center">
      <div class="line-height-30 tirtleFont textclolor-black-low">
        © 2017 All rights reserved. Development by ZIMOON
      </div>
      <div class="line-height-30 iconFont textclolor-white ">Projects made with </div>
      <v-link/>
    </div>
  </div>
</template>
<script>
  import vLink from '@/components/link'
  export default {
    components: {
      vLink
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

  .text-right {
    text-align: right;
  }

</style>
