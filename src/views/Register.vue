<template>
  <div class="auth-page">
    <div class="container page">
      <div class="row">
        <div class="col-md-6 offset-md-3 col-xs-12">
          <h1 class="text-sx-center">Sign Up</h1>
          <p class="text-xs-center">
            <router-link :to="{name: 'login'}">Need an account?</router-link>
          </p>
          Valid errors
          <form @submit.prevent="onSubmit">
            <fieldset class="form-group">
              <input type="text" class="form-control form-control-lg">
            </fieldset>
          </form>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'McRegister'
}
</script>