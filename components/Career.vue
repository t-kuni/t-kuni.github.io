<template>
  <section class="flex">
    <div class="side-bar-area flex-none">
      <div class="side-bar" ref="sideBar"></div>
      <div class="side-bar-circle"></div>
    </div>
    <div class="text-area flex-auto ml-2" ref="textArea">
      <h2 class="title-text">経歴</h2>
      <div class="flex mt-2">
        <h3 class="font-bold flex-auto">自社サービス企業</h3>
        <p>2017 〜 現在</p>
      </div>
      <p class="mt-2">PHP/Laravelを用いた求人サービスに機能追加を行っています。<br/>
        自身はバックエンド担当で、チームはPM兼営業、マーケター、ライター、運営、デザイナー、フロントエンド、バックエンドがそれぞれ1名づつという体制です。<br/>
        自身の実績としては、会員登録機能やメッセージ機能、求人サービスによくあるスカウト機能などを実装しました。<br/>
        分析基盤を作成し、コンバージョンの集計や営業レポートの作成を自動化しました。<br/>
        その他、開発を円滑に進めるための足回りの整備も積極的に行っています。<br/>
        開発環境のコード化、DBのスキーマ更新にmigrationを導入、ユニットテストの導入、既存コードのリファクタリングなど</p>
      <div class="flex mt-2">
        <h3 class="font-bold flex-auto">SES（技術者派遣）企業</h3>
        <p>2012 〜 2017</p>
      </div>
      <p class="mt-2">出向先や自社内にて、さまざまなプロジェクトに携わりました
        ・Webサービス開発（Laravel）
        ・ライブラリ開発（JavaScript）
        ・業務システム開発（SAStruts）
        ・スマートフォンアプリ開発（Objective-C, Java）
        ・UIテスト自動化（VBA）</p>
      <div class="flex mt-2">
        <h3 class="font-bold flex-auto">情報系専門学校</h3>
        <p>2010 〜 2012</p>
      </div>
      <p class="mt-2">Webサービスを作りたかったのでPHP、MySQL、Linux、Webデザイン等を積極的に学んでいました。
        就職活動でアピールするため資格を積極的に取得しました。
        そういった姿勢が学校側に認められ学費の一部免除を受けることが出来ました。
        在籍中に作成した、とあるアーケードゲームのWebツールが月間10万PV程度ありました。</p>
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

  .text-area {
    h3 {
      position: relative;

      &:after {
        content: "";
        display: block;
        position: absolute;
        top: 3px;
        left: -26px;
        width: 14px;
        height: 14px;
        border-radius: 999px;
        @apply bg-accent;
      }
    }
  }
</style>
