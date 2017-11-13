<template>
  <div class="page-tabbar">
    <teheader :showbar='showBar' :name="transitionName"></teheader>
    <div class="page-content">
      <transition :name="transitionName" :mode="transModule">
        <keep-alive exclude="Com">
          <router-view class="view"></router-view>
        </keep-alive>
      </transition>
    </div>
  </div>
</template>
<script>
  import teheader from './components/teheader.vue'
  import 'animate.css'
  export default {
    data () {
      return {
        transitionName: 'slide-fade',
        transModule: 'out-in',
        showBar: false
      }
    },
    components: {
      teheader
    },
    methods: {
      handleScroll () {
        this.showBar = window.scrollY > 30;
      }
    }

  }
</script>
<style>
  body {
    font-family: Helvetica, sans-serif;
    -webkit-overflow-scrolling: touch;
  }

  a {
    text-decoration: blink;
  }

  .slide-fade-enter-active {
    animation: bounce-in 0.15s ease;
  }

  .slide-fade-leave-active {
    animation: bounce-out 0.15s ease;
  }

  @keyframes bounce-in {
    0% {
      transform: translateY(800px);
    }
    100% {
      transform: translateY(0px);
    }
  }

  @keyframes bounce-out {
    0% {
      transform: translateY(0px);
    }
    100% {
      transform: translateY(-800px);
    }
  }

  @keyframes pounce-in {
    0% {
      transform: translateY(-10px);
    }
    100% {
      transform: translateY(0px);
    }
  }

  @keyframes pounce-out {
    0% {
      transform: translateY(0px);
    }
    100% {
      transform: translateY(800px);
    }
  }

  .slide-left-enter-active {
    animation: pounce-in 0.15s ease;
  }

  .slide-left-leave-active {
    animation: pounce-out 0.15s ease;
  }

  .slide-left-enter, .slide-left-leave-active {
    opacity: 1;
  }

</style>
