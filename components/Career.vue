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
        <p>2017年 〜 現在</p>
      </div>
      <p class="mt-2">PHP/Laravelを用いた求人サービスに機能追加を行っています。<p/>
      <p class="mt-2">自身はバックエンド担当で、チームはPM兼営業、マーケター、ライター、運営、デザイナー、フロントエンド、バックエンドがそれぞれ1名づつという体制です。<p/>
      <p class="mt-2">自身の実績は以下の通りです。<p/>
      <p class="mt-2">
        ・会員登録機能やメッセージ機能、求人サービスによくあるスカウト機能などの実装<br/>
        ・業務を効率化するツールの開発<br/>
        ・BigQueryとデータポータルを用いた分析基盤を構築し、データの活用を推進<br/>
        ・プロダクトを成長させていくための開発環境周りの整備<br/>
      </p>
      <p class="note-area mt-3">上記の業務の傍ら、副業として他社のサービスの開発の手伝いや、教材の執筆を行っていました。</p>
      <div class="flex mt-6">
        <h3 class="font-bold flex-auto">SES（技術者派遣）企業</h3>
        <p>2012年 〜 2017年</p>
      </div>
      <p class="mt-2">出向先や自社内にて、以下のようなプロジェクトに携わりました<p/>
      <p class="mt-2">
        ・Webサービス開発（Laravel）<br/>
        ・ライブラリ開発（JavaScript）<br/>
        ・業務システム開発（SAStruts）<br/>
        ・スマートフォンアプリ開発（Objective-C, Java）<br/>
        ・UIテスト自動化（VBA）</p>
      <div class="flex mt-6">
        <h3 class="font-bold flex-auto">情報系専門学校</h3>
        <p>2010年 〜 2012年</p>
      </div>
      <p class="mt-2">Webサービスを作りたかったのでPHP、MySQL、Linux、Webデザイン等を積極的に学んでいました。</p>
      <p class="mt-2">就職活動を有利に進めるため資格を積極的に取得しました。<br/>
        そういった姿勢が学校側に認められ学費の一部免除を受けることが出来ました。<p/>
      <p class="mt-2">在学中に作成した、とあるアーケードゲームのWebツールが月間10万PV程度ありました。</p>
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
