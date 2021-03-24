<template>
  <div class="container">
    <section>
      <div class="avatar-area">
        <div class="triangle"></div>
        <div class="flex justify-center">
          <img src="~/assets/img/avatar.jpg" class="rounded-full" style="width: 200px; height: 200px;">
        </div>
      </div>
      <h1 class="font-bold text-lg text-accent text-center">T・Kuni</h1>
      <p class="text-center">Webエンジニア　1990年生まれ</p>
      <p class="m-3">アプリケーションレイヤが主戦場のWebエンジニアです。<br/>
        エンドユーザ目線でUXの改善、機能の提案＆実装を心掛けています。<br/>
        プログラミングやDB設計、SEO、インフラ構築、UX/UIデザインなど幅広く対応しています。<br/>
        目的や課題から逆算して必要なものを習得、実装するスタイルなので広く浅くフルスタック気味です。<br/>
        特定の技術に凄く詳しいというよりは、必要なスキルを広く浅く習得しています。</p>
    </section>
    <section>
      <h2 class="line-header">資格</h2>
      <ul>
        <li>基本情報処理</li>
        <li>応用情報処理</li>
      </ul>
    </section>
    <section>
      <h2 class="line-header">リンク</h2>
      <ul>
        <li>aaa</li>
      </ul>
    </section>
    <to-work></to-work>
    <career></career>
    <skill-stack></skill-stack>
  </div>
</template>

<script>
import ToWork from "../components/ToWork";
import Career from "../components/Career";
import SkillStack from "../components/SkillStack";

export default {
  components: {ToWork, Career, SkillStack},
}
</script>

<style type="scss" scoped>
.triangle {
  width: 0;
  height: 0;
  border-left: 30px solid transparent;
  border-right: 30px solid transparent;
  border-bottom: 30px solid #C0C0C0;
  transform: translate(-10px, 5px) rotate(-45deg);
}
</style>
