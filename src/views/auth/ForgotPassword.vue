<template>
<div>
  <div class="container mt-5">
      <formForgot/>
  </div>
</div>
</template>

<script>
// @ is an alias to /src
import formForgot from '@/components/formForgot.vue'

export default {
  name: 'Home',
  components: {
    formForgot
  }
}
</script>

<style scoped>

</style>
