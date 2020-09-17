<template>
<div>
  <form>
    <div class="container w-50 bg-white rounded-box shadow-sm">
        <div class="row">
          <router-link to="/" class="col-1 mt-4 text-center">
            <h5><arrowicon class="color-text"/></h5>
          </router-link>
          <h4 class="text-center color-text pt-4 col-10">Forgot Password</h4>
        </div>
        <div class="container w-75">
          <p class="mt-4">You’ll get messages soon on your e-mail </p>
          <div class="form-group mt-4">
            <label for="exampleInputEmail1" class="text-muted">Email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          </div>
          <div class="pb-5 pt-4">
            <button type="button" class="btn btn-primary btn-lg btn-block rounded-pill color-bg mb-3">Send</button>
          </div>
        </div>
    </div>
  </form>
</div>
</template>

<script>
import arrowicon from '../components/atoms/arrowicon'
export default {
  name: 'formForgot',
  components: {
    arrowicon
  }
}
</script>

<style scoped>
.rounded-box {
  border-radius: 30px;
}
.color-bg {
  background-color: #7E98DF;
}
.color-text {
  color: #7E98DF;
}
</style>
