<template>
  <div>
    <div class="fixed width-100 zindex-100 text-align-center"
         v-bind:class="{ bghand: showbar, bgtrans: !showbar }">
      <div
        class="width-80 margin-auto box-flex text-align-center flex-direction-row flex-wrap flex-justify-center flex-items-center height-100">
        <!-- bottomSheet -->
        <div class="flex-1 text-align-left flex-self-center ">
          <span class="ion-navicon-round font-size-26" @click="openBottomSheet"></span>
        </div>
        <!-- /ends bottomSheet -->

        <div class="flex-3 flex-offset-1 flex-direction-row flex-items-flex-start unselect"></div>

        <div class="flex-1 text-align-left flex-self-center"></div>

      </div>
    </div>
    <mu-bottom-sheet :open="bottomSheet" @close="closeBottomSheet">
      <div class="line-height-50 text-align-right bg-333" @click="closeBottomSheet">
        <span class="ion-close-round font-size-20 margin-right-5 textclolor-white"></span>
      </div>
      <ul class="list-all bg-333" @Click="closeBottomSheet">
        <router-link to="/">
          <li class="line-height-50 text-align-center font-size-20 textclolor-white" @click="closeBottomSheet">
            Home
          </li>
        </router-link>
        <!--<a href="#" target="_blank">-->
        <li class="line-height-50 text-align-center font-size-20 textclolor-white">
          Blog
          <span style="font-size: 12px">敬请期待...</span>
        </li>
        <!--</a>-->
      </ul>

      <mu-list @itemClick="closeBottomSheet" class="bg-333">
        <div
          class="width-100 text-align-center margin-top-2 flex-justify-center  flex-items-center flex-content-center bg-333 font-size-12 textclolor-black-low">
          connext with me
        </div>
        <div
          class="width-100 text-align-center margin-top-2 margin-bottom-3 flex-justify-center  flex-items-center flex-content-center bg-333">
          <my-link></my-link>
        </div>
      </mu-list>
    </mu-bottom-sheet>
  </div>
</template>
<script>
  import myLink from '@/components/mylink'
  export default {
    data () {
      return {
        focusStatus: true,
        title: [],
        slidName: 'list',
        bottomSheet: false
      }
    },
    components: {
      myLink
    },
    props: ['showbar', 'name'],
    methods: {
      closeBottomSheet () {
        this.bottomSheet = false
      },
      openBottomSheet () {
        this.bottomSheet = true
      }
    },
    watch: {
      name: function (newQuestion) {
        if (newQuestion === 'slide-fade') {
          this.focusStatus = true
          this.slidName = 'list'
        } else {
          this.focusStatus = false
          this.slidName = 'topleave'
        }
      },
      totitle: function (newQuestion) {
        let o = this.title
        setTimeout(function () {
          o.splice(0, 1)
        }, 10)
        this.title.splice(1, 0, {'name': newQuestion})
      }
    },
    created: function () {
      this.title.push({'name': this.totitle})
    }

  }
</script>
<style>
  .page-header-main {
    overflow: hidden;
    margin-top: 120px;
    min-height: 95vh;
  }

  .page-content {
    overflow: hidden;
    min-height: 100vh;
  }

  .header {
    -webkit-box-align: center;
    -ms-flex-align: center;
    align-items: center;
    background-color: #26a2ff;
    box-sizing: border-box;
    color: #fff;
    display: flex;
    font-size: 14px;
    height: 50px;
    line-height: 1;
    padding: 0 10px;
    position: relative;
    text-align: center;
    white-space: nowrap;
  }

  .header a {
    color: #fff;
  }

  .header-left {
    text-align: left;
    -webkit-box-flex: .5;
    -ms-flex: .5;
    flex: .5;
    z-index: 10;
  }

  .header-title {
    overflow: hidden;
    text-overflow: ellipsis;
    white-space: nowrap;
    font-size: inherit;
    font-weight: 400;
    -webkit-box-flex: 1;
    -ms-flex: 1;
    flex: 1;
    text-align: center;
    position: absolute;
    width: 100%;
    z-index: 5;
    left: 0;
    top: 0;
    height: 50px;
  }

  .is-fixd {
    top: 0;
    right: 0;
    left: 0;
    position: fixed;
    z-index: 1;
  }

  .header-right {
    text-align: right;
    -webkit-box-flex: .5;
    -ms-flex: .5;
    flex: .5;
    z-index: 10;
  }

  .list-item {
    display: inline-block;
    width: 100%;
    height: 50px;
    line-height: 50px;
    left: 0px;
    top: 0px;
    z-index: 5;
    position: absolute;
  }

  .list-enter-active {
    animation: left-in 0.5s ease;
  }

  .list-leave-active {
    animation: left-out 0.5s ease;
  }

  .bghand {
    background: rgba(255, 255, 255, 0.7);
    transition: all 0.5s ease;
  }

  .bgtrans {
    background: transparent;
    transition: all 0.5s ease;
  }

  /*.list-move {
    transition: transform 1s;
  }*/
  /*从右向左滑动*/
  @keyframes left-in {
    0% {
      transform: translateY(270px);
      opacity: 0;
    }
    100% {
      transform: translateY(0px);
      opacity: 1;
    }
  }

  @keyframes left-out {
    0% {
      transform: translateY(0px);
      opacity: 1;
    }
    100% {
      transform: translateY(-270px);
      opacity: 0;
    }
  }

  .topleave-enter-active {
    animation: right-in 0.5s ease;
  }

  .topleave-leave-active {
    animation: right-out 0.5s ease;
  }

  /*从左向右滑动*/
  @keyframes right-in {
    0% {
      transform: translateY(-270px);
      opacity: 0;
    }
    100% {
      transform: translateY(0px);
      opacity: 1;
    }
  }

  @keyframes right-out {
    0% {
      transform: translateY(0px);
      opacity: 1;
    }
    100% {
      transform: translateY(270px);
      opacity: 0;
    }
  }
</style>
