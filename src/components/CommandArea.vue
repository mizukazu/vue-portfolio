<template>
  <div class="command-area">
    <ul class="command">
      <li><router-link to="/skill">スキル</router-link></li>
      <li><router-link to="/product">成果物</router-link> </li>
      <li><router-link to="/work">経歴</router-link></li>
      <li><router-link to="/contact">お問い合わせ</router-link></li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'command-area',
  data() {
    return {
      CommandList: []
    }
  }
}
</script>

<style lang="scss">
.command-area {
  width: 20%;
  border: 2px solid #fff;
  border-radius: 5px;
  padding: 16px 0;
  font-size: 18px;
  .command {
    display: flex;
    flex-direction: column;
    margin: 0;
    padding-left: 32px;
    list-style-type: none;
    li {
      padding: 8px 0;
      a {
        text-decoration: none;
        color: #fff;
      }
    }
  }
}
</style>