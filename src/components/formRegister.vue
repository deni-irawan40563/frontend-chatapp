<template>
<div>
  <form>
    <div class="container w-50 bg-white rounded-box shadow-sm">
        <b-icon icon="chevron-left" variant="info"></b-icon>
        <h4 class="text-center color-text pt-4"> Register</h4>
        <div class="container w-75">
          <p class="font-weight-bold mt-4">Let’s create your account!</p>
          <div class="form-group mt-4">
            <label for="exampleInputEmail1" class="text-muted">Email</label>
            <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
          </div>
          <div class="form-group">
            <label for="exampleInputPassword1" class="text-muted">Password</label>
            <input type="password" class="form-control" id="exampleInputPassword1">
          </div>
          <div class="text-right mt-4 mb-4">
            <router-link to="/" ><span>Forgot password?</span></router-link>
          </div>
          <div class="pb-5">
            <button type="button" class="btn btn-primary btn-lg btn-block rounded-pill color-bg mb-3">Login</button>
            <div class="row mt-5 mb-5">
              <div class="border-top mt-3 col-4"></div>
              <p class="text-center col-4">Login with</p>
              <div class="border-top mt-3 col-4"></div>
            </div>
            <button type="button" class="btn btn-outline-info btn-lg btn-block rounded-pill mb-3"><img src="../../src/assets/Vector.svg" class="mb-1 mr-2">   Google</button>
            <p class="text-center mt-5">Don’t have an account? <a href="">Sign Up</a></p>
          </div>
        </div>
    </div>
  </form>
</div>
</template>

<script>
export default {
  name: 'formRegister'
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
