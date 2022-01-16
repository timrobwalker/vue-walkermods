<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Website msg="Time To Build."/>
  </div>
</template>

<script>
// @ is an alias to /src
import Website from '@/components/main.vue'

export default {
  name: 'Home',
  components: {
    Website
  }
}
</script>
