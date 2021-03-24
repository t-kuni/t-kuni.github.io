<template>
  <div class="container mb-5">
    <section>
      <div class="avatar-area">
        <div class="triangle"></div>
        <div class="flex justify-center">
          <img src="~/assets/img/avatar.jpg" class="rounded-full" style="width: 200px; height: 200px;">
        </div>
      </div>
      <h1 class="font-bold text-lg text-accent text-center mt-3">T・Kuni</h1>
      <p class="text-center mt-3">Webエンジニア　1990年生まれ</p>
      <p class="mt-3 mx-3">アプリケーションレイヤが主戦場のWebエンジニアです。<br/>
        エンドユーザ目線でUXの改善、機能の提案＆実装を心掛けています。<br/>
        プログラミングやDB設計、SEO、インフラ構築、UX/UIデザインなど幅広く対応しています。<br/>
        目的や課題から逆算して必要なものを習得、実装するスタイルなので広く浅くフルスタック気味です。<br/>
        特定の技術に凄く詳しいというよりは、必要なスキルを広く浅く習得しています。</p>
    </section>
    <certificates class="mt-3 mx-3"></certificates>
    <links class="mt-3 mx-3"></links>
    <to-work class="mt-4 mx-3"></to-work>
    <career class="mt-3 mx-3"></career>
    <skill-stack class="mt-3 mx-3"></skill-stack>
  </div>
</template>

<script>
import ToWork from "../components/ToWork";
import Career from "../components/Career";
import SkillStack from "../components/SkillStack";
import Certificates from "../components/Certificates";
import Links from "../components/Links";

export default {
  components: {ToWork, Career, SkillStack, Certificates, Links},
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
