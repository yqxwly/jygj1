<template>
  <view>
    <view class="backmax">

      <view class="redbox">
        <view class="boxleft1"></view>
        <view class="boxleft2"></view>

        <view class="boxright1">
          <view class="kuang"></view>
        </view>

        <view class="boxright2"></view>
        <view class="right1"></view>
        <view class="right2"></view>

      </view>

    </view>
  </view>
</template>

<script>
  export default {
    data() {
      return {

      }
    },
    methods: {

    }
  }
</script>

<style lang="scss">
  .backmax {
    .position-relative {
      position: relative;
      left: -691px;
      top: -523px;
      width: 1440px;
      height: 2000px; //改了 
      opacity: 1;
      background: rgb(255, 255, 255);
    }

  }

  .redbox {
    position: relative;
    left: 0px;
    top: 79px;
    width: 1440px;
    height: 972px;
    opacity: 1;
    border-radius: 44px;
    background: rgb(242, 78, 78);
  }

  .boxleft1 {
    position: absolute;
    left: 15px;
    top: 110px; //175
    width: 283px;
    height: 268px;
    opacity: 1;
    border-radius: 52px;
    background: rgb(255, 255, 255);
  }

  .boxleft2 {
    position: absolute;
    left: 15px;
    top: 480px; //543
    width: 283px;
    height: 470px;
    opacity: 1;
    border-radius: 52px;
    background: rgb(255, 255, 255);
  }

  .boxright1 {
    position: absolute;
    left: 306px;
    top: 110px;
    width: 1103px;
    height: 268px;
    opacity: 1;
    border-radius: 10px;
    background: rgb(255, 255, 255);
  }

  .boxright2 {
    position: absolute;
    left: 306px;
    top: 480px;
    width: 1103px;
    height: 470px;
    opacity: 1;
    border-radius: 10px;
    background: rgb(255, 255, 255);
    box-shadow: 0px 2px 4px rgb(0, 0, 0);
  }

  .right1 {
    position: absolute;
    left: 306px;
    top: 30px;
    width: 1103px;
    height: 80px;
    opacity: 1;
    border-radius: 10px;
    background: rgb(255, 145, 145);
  }

  .right2 {
    position: absolute;
    left: 308px;
    top: 400px;
    width: 1103px;
    height: 80px;
    opacity: 1;
    border-radius: 10px;
    background: rgb(255, 145, 145);
  }


  .kuang {
    position: absolute;
    left: 720px;
    top: 20px;
    width: 336px;
    height: 222px;
    opacity: 1;
    border-radius: 52px;
    background: rgb(255, 255, 255);
    border: 3px dashed rgb(242, 78, 78);

  }
</style>