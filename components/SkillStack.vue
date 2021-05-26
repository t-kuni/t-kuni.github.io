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
          <td class="pl-1">PHP-FPM, Nginx, Apache, Redis, MySQL, Postfix</td>
        </tr>
        <tr>
          <th class="py-1">コンテナ</th>
          <td class="pl-1">Docker</td>
        </tr>
        <tr>
          <th class="py-1">インフラ</th>
          <td class="pl-1">AWS, GCP, Terraform</td>
        </tr>
        <tr>
          <th class="py-1">分析基盤</th>
          <td class="pl-1">BigQuery, データポータル</td>
        </tr>
        <tr>
          <th class="py-1">テスト</th>
          <td class="pl-1">PHPUnit, jMeter</td>
        </tr>
        <tr>
          <th class="py-1">IDE</th>
          <td class="pl-1">PhpStorm</td>
        </tr>
        <tr>
          <th class="py-1">バージョン管理</th>
          <td class="pl-1">Git, SVN</td>
        </tr>
        <tr>
          <th class="py-1">情報共有</th>
          <td class="pl-1">Slack, esa, figma, spreadsheet</td>
        </tr>
        <tr>
          <th class="py-1">タスク管理</th>
          <td class="pl-1">Backlog, Trello</td>
        </tr>
        <tr>
          <th class="py-1">アクセス解析</th>
          <td class="pl-1">Google Analytics</td>
        </tr>
        <tr>
          <th class="py-1">SEO</th>
          <td class="pl-1">Search Console, Lighthouse</td>
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
