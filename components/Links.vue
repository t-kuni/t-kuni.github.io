<template>
  <section>
    <h2 class="line-header title-text">リンク</h2>
    <ul>
      <li>
        <font-awesome-icon :icon="['fas', 'rss']" style="color: #E37400"/>
        <a class="ml-1" href="https://t-kuni-tech.com" target="_blank">技術ブログ</a>
        <ul>
          <li class="ml-5">
            <font-awesome-icon :icon="['fas', 'wrench']" style="color: #E37400"/>
            <a href="https://t-kuni-tech.com/%e4%bd%9c%e3%81%a3%e3%81%9f%e3%82%82%e3%81%ae%e3%83%aa%e3%82%b9%e3%83%88/" target="_blank">作ったものリスト</a>
          </li>
          <li class="ml-5">
            <font-awesome-icon :icon="['fas', 'book']" style="color: #E37400"/>
            <a href="https://t-kuni-tech.com/%e8%aa%ad%e3%82%93%e3%81%a0%e6%9c%ac%e3%83%aa%e3%82%b9%e3%83%88/" target="_blank">読んだ本リスト</a>
          </li>
        </ul>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'twitter']" style="color: #1CA1F2;"/>
        <a class="ml-1" href="https://twitter.com/t_kuni_" target="_blank">Twitter(@t_kuni_)</a>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'github']" />
        <a class="ml-1" href="https://github.com/t-kuni" target="_blank">Github</a>
      </li>
      <li>
        <font-awesome-icon :icon="['fas', 'circle']" style="color: #55C504"/>
        <a class="ml-1" href="https://qiita.com/t-kuni" target="_blank">Qiita</a>
      </li>
    </ul>
  </section>
</template>

<script>
export default {
}
</script>

<style type="scss" scoped>
</style>
