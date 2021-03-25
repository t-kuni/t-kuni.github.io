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
          <th class="py-1">言語</th>
          <td class="pl-1">PHP, JavaScript(ブラウザ、Node), SQL</td>
        </tr>
        <tr>
          <th class="py-1">ライブラリ<br/>フレームワーク</th>
          <td class="pl-1">Laravel, Vue, Nuxt</td>
        </tr>
        <tr>
          <th class="py-1">ミドルウェア</th>
          <td class="pl-1">Nginx, Apache, Redis, MySQL</td>
        </tr>
        <tr>
          <th class="py-1">インフラ</th>
          <td class="pl-1">AWS, Terraform, GCP</td>
        </tr>
        <tr>
          <th class="py-1">ツール</th>
          <td class="pl-1">Git, PhpStorm, Docker</td>
        </tr>
        <tr>
          <th class="py-1">SaaS</th>
          <td class="pl-1">esa, figma, spreadsheet, Slack, Google Analytics</td>
        </tr>
        <tr>
          <th class="py-1">SEO</th>
          <td class="pl-1">Google Analytics, Search Console, Lighthouse</td>
        </tr>
        <tr>
          <th class="py-1">分析基盤</th>
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

  table {
    td,th {
      border: 1px solid black;
      border-collapse: collapse;
    }
  }
</style>
