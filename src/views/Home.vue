<template>
<div>
  <div class="container">
      <formSubmit />
  </div>
</div>
</template>

<script>
// @ is an alias to /src
import formSubmit from '@/components/formSubmit.vue'

export default {
  name: 'Home',
  components: {
    formSubmit
  }
}
</script>
