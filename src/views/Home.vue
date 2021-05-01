<template>
  <div class="home">
    <RankList/>
  </div>
</template>

<script>
// @ is an alias to /src
import RankList from '@/components/RankList.vue'

export default {
  name: 'Home',
  components: {
    RankList
  }
}
</script>
