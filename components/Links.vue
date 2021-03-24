<template>
  <section>
    <h2 class="line-header title-text">リンク</h2>
    <ul>
      <li>
        <font-awesome-icon :icon="['fas', 'rss']" style="color: #E37400"/>
        <a class="ml-1" href="https://t-kuni-tech.com">技術ブログ</a>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'twitter']" style="color: #1CA1F2;"/>
        <a class="ml-1" href="https://twitter.com/t_kuni_">Twitter(@t_kuni_)</a>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'github']" />
        <a class="ml-1" href="https://github.com/t-kuni">Github</a>
      </li>
      <li>
        <font-awesome-icon :icon="['fas', 'circle']" style="color: #55C504"/>
        <a class="ml-1" href="https://qiita.com/t-kuni">Qiita</a>
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
