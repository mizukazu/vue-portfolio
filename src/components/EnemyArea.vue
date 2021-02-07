<template>
  <div class="enemy-area">
    <div class="profile">
      <img :src="imgUrl" alt="">
    </div>
  </div>
</template>

<script>
export default {
  name: 'enemy-area',
  data() {
    return {
      imgUrl: require('../assets/img/profile.jpg')
    }
  }
}
</script>

<style lang="scss">
.enemy-area {
  margin: 48px 0;
  .profile {
    width: 280px;
    margin: 0 auto;
    img {
      width: 100%;
    }
  }
}
</style>