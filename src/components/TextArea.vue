<template>
  <div class="text-area">
    <div class="name">みずかず＠WEBエンジニア</div>
    <div class="num">-1人</div>
  </div>
</template>

<script>
export default {
  name: 'text-area'
}
</script>

<style lang="scss">
.text-area {
  display: flex;
  justify-content: space-between;
  align-items: center;
  width: 80%;
  max-height: 70px;
  border: 2px solid #fff;
  border-radius: 5px;
  margin: 0 24px;
  padding: 0 16px;
  font-size: 18px;
  .name {
    padding: 0 32px;
  }
}
</style>