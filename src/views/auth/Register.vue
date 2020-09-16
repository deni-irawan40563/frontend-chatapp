<template>
<div>
  <div class="container">
      <formRegister />
  </div>
</div>
</template>

<script>
// @ is an alias to /src
import formRegister from '@/components/formRegister.vue'

export default {
  name: 'Home',
  components: {
    formRegister
  }
}
</script>
