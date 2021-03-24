<template>
  <section class="flex">
    <div class="side-bar-area flex-none">
      <div class="side-bar" ref="sideBar"></div>
      <div class="side-bar-circle"></div>
    </div>
    <div class="text-area flex-auto" ref="textArea">
      <h2 class="title-text">使い慣れている技術スタック</h2>
      <table>
        <tbody>
        <tr>
          <th>言語</th>
          <td>PHP, JavaScript(ブラウザ、Node), SQL</td>
        </tr>
        </tbody>
      </table>
      <p>オンプレ環境のインフラ構成やネットワークはあまり経験が無く疎いです</p>
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
