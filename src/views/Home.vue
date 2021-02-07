<template>
  <div class="home">
    <status-area/>
    <enemy-area/>
    <div class="flex">
      <command-area/>
      <text-area/>
    </div>
  </div>
</template>

<script>
import StatusArea from '@/components/StatusArea.vue'
import EnemyArea from '@/components/EnemyArea.vue'
import CommandArea from '@/components/CommandArea.vue'
import TextArea from '@/components/TextArea.vue'

export default {
  name: 'Home',
  components: {
    StatusArea,
    EnemyArea,
    CommandArea,
    TextArea
  }
}
</script>

<style lang="scss">
.home {
  margin-top: 64px;
  text-align: left;
}
.flex {
  display: flex;
}
</style>