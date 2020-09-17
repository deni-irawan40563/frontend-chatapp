<template>
<div class="row">
    <div class="col-3 bg-white height shadow-sm">
        <navbar />
        <chatCard />
        <chatCard />
        <chatCard />
    </div>
    <div class="col-9" >
      <navbarProfileChat />
      <chatCloud />
      <chatCloud />
      <chatInput />
    </div>
</div>
</template>

<script>
import navbar from '../../components/molucules/navbar'
import chatCard from '../../components/molucules/chatCard'
import navbarProfileChat from '../../components/atoms/navbarProfileChat'
import chatInput from '../../components/atoms/chatInput'
import chatCloud from '../../components/atoms/chatCloud'

export default {
  name: 'mainpage',
  components: {
    navbar,
    chatCard,
    navbarProfileChat,
    chatInput,
    chatCloud
  }
}
</script>

<style scoped>
.color-text {
    color: #7E98DF;
}
.height {
    height: 770px;
}
</style>
