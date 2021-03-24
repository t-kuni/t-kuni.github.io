<template>
  <section class="flex">
    <div class="side-bar-area flex-none">
      <div class="side-bar" ref="sideBar"></div>
      <div class="side-bar-circle"></div>
    </div>
    <div class="text-area flex-auto" ref="textArea">
      <h2 class="title-text">経歴</h2>
      <div class="flex">
        <h3 class="font-bold flex-auto">自社サービス企業</h3>
        <p>2017 〜 現在</p>
      </div>
      <p>経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文</p>
      <div class="flex">
        <h3 class="font-bold flex-auto">SES（技術者派遣）企業</h3>
        <p>2012 〜 2017</p>
      </div>
      <p>経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文</p>
      <div class="flex">
        <h3 class="font-bold flex-auto">情報系専門</h3>
        <p>2010 〜 2012</p>
      </div>
      <p>経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文</p>
      <div class="flex">
        <h3 class="font-bold flex-auto">情報系専門</h3>
        <p>2010 〜 2012</p>
      </div>
      <p>経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文経歴本文</p>
    </div>
  </section>
</template>

<script>
export default {
}
</script>

<style type="scss" scoped>
  .side-bar-area {
    position: relative;
    width: 20px;

    .side-bar-circle {
      position: absolute;
      left: 1px;
      width: 18px;
      height: 18px;
      border-radius: 10px;
      margin: 0 auto;
      @apply bg-accent;
    }

    .side-bar {
      position: absolute;
      left: 8px;
      width: 4px;
      height: 100%;
      border-radius: 2px;
      @apply bg-accent-light;
    }
  }

  .text-area {
    h3 {
      position: relative;

      &:after {
        content: "";
        display: block;
        position: absolute;
        top: 3px;
        left: -17px;
        width: 14px;
        height: 14px;
        border-radius: 999px;
        @apply bg-accent;
      }
    }
  }
</style>
