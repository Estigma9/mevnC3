<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <the-footer></the-footer>
  </div>
</template>

<script>
// @ is an alias to /src
import TheFooter from '@/components/TheFooter.vue'

export default {
  name: 'HomeView',
  components: {
    TheFooter
  }
}
</script>

