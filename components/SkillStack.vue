<template>
  <section class="flex">
    <div class="side-bar-area flex-none">
      <div class="side-bar" ref="sideBar"></div>
      <div class="side-bar-circle"></div>
    </div>
    <div class="text-area flex-auto ml-2" ref="textArea">
      <h2 class="title-text">使い慣れている技術スタック</h2>
      <table class="mt-2">
        <tbody>
        <tr>
          <th>言語</th>
          <td class="pl-1">PHP, JavaScript(ブラウザ、Node), SQL</td>
        </tr>
        <tr>
          <th>ライブラリ<br/>フレームワーク</th>
          <td class="pl-1">Laravel, Vue, Nuxt</td>
        </tr>
        <tr>
          <th>ミドルウェア</th>
          <td class="pl-1">Nginx, Apache, Redis, MySQL</td>
        </tr>
        <tr>
          <th>インフラ</th>
          <td class="pl-1">AWS, Terraform, GCP</td>
        </tr>
        <tr>
          <th>ツール</th>
          <td class="pl-1">Git, PhpStorm, Docker</td>
        </tr>
        <tr>
          <th>SaaS</th>
          <td class="pl-1">esa, figma, spreadsheet, Slack, Google Analytics</td>
        </tr>
        <tr>
          <th>SEO</th>
          <td class="pl-1">Google Analytics, Search Console, Lighthouse</td>
        </tr>
        <tr>
          <th>分析基盤</th>
          <td class="pl-1">BigQuery(GCP) データポータル</td>
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

  table {
    td,th {
      border: 1px solid black;
      border-collapse: collapse;
    }
  }
</style>
