<template>
  <section>
    <h2 class="line-header title-text">資格</h2>
    <ul>
      <li>
        <font-awesome-icon :icon="['fas', 'book']" />
        <span class="ml-1">基本情報処理</span>
      </li>
      <li>
        <font-awesome-icon :icon="['fas', 'pencil-alt']" />
        <span class="ml-1">応用情報処理</span>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'java']" />
        <span class="ml-1">Javaプログラミング能力認定試験 2級</span>
      </li>
      <li>
        <font-awesome-icon :icon="['fas', 'server']" />
        <span class="ml-1">LPIC-1</span>
      </li>
      <li>
        <font-awesome-icon :icon="['fas', 'database']" />
        <span class="ml-1">ORACLE MASTER Bronze</span>
      </li>
      <li>
        <font-awesome-icon :icon="['fab', 'aws']" />
        <span class="ml-1">AWS Cloud Practitioner</span>
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
