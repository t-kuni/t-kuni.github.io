<template>
  <section class="flex">
    <div class="side-bar-area flex-none">
      <div class="side-bar" ref="sideBar"></div>
      <div class="side-bar-circle"></div>
    </div>
    <div class="flex-auto ml-2" ref="textArea">
      <h2 class="title-text mt-1">仕事との向き合い方</h2>
      <p class="mt-2">趣味である個人制作を通して習得した知識を仕事で活用する事が多いです。</p>
      <p class="mt-2">個人制作では試したい事や使用する技術を決めて、ガッと開発に取り組んで、ブログなりQiitaなりにアウトプットする事で知識が身につくようにしています。</p>
      <p class="mt-2">プライベートの時間を使った自己研鑽もある程度評価して頂ける風土があると嬉しいです。</p>
      <p class="mt-2">必要に応じてユニットテストを書きます。<br/>
        全てのモジュール、パターンに対して書くとコストが跳ね上がってしまうので、ビジネス的に重要なモジュールや、複雑になる事が予想されるモジュールに対して書くようにしています。</p>
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
    width: 24px;

    .side-bar-circle {
      position: absolute;
      left: 1px;
      width: 24px;
      height: 24px;
      border-radius: 999px;
      @apply bg-accent;
    }

    .side-bar {
      position: absolute;
      left: 11px;
      width: 4px;
      height: 100%;
      border-radius: 2px;
      @apply bg-accent-light;
    }
  }
</style>
