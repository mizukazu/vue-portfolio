<template>
  <nav class="nav">
    <router-link to="/">ホーム</router-link> |
    <router-link to="/skill">スキル</router-link> |
    <router-link to="/work">経歴</router-link> |
    <router-link to="/contact">お問い合わせ</router-link> |
  </nav>
</template>

<script>
export default {
  name: 'navigation'
}
</script>

<style lang="scss">
.nav {
  padding: 30px;
  a {
    font-weight: bold;
    color: #2c3e50;
    &.router-link-exact-active {
      color: #42b983;
    }
  }
}
</style>