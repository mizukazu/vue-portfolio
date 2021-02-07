<template>
  <div class="status-area">
    <ul class="status">
      <li>{{ name }}</li>
      <li>H{{ hp }}</li>
      <li>M{{ mp }}</li>
      <li>ゆ:{{ Lv }}</li>
    </ul>
  </div>
</template>

<script>
export default {
  name: 'status-area',
  data () {
    return {
      name: 'トンヌラ',
      hp: 152,
      mp: 98,
      Lv: 18 
    }
  }
}
</script>

<style lang="scss">
.status-area {
  width: 100%;
  border: 2px solid #fff;
  border-radius: 5px;
  padding: 24px 0;
  font-size: 24px;
  .status {
    list-style-type: none;
    margin: 0;
  }
}
</style>