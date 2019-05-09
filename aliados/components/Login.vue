<template>
  <div class="wrapper">
    <form class="form-singin">
      <img class="signin-logo" src="~/assets/Logo-Nutired.png"></img>
      <h2 class="form-singin-heading text-center">Iniciar Sesión</h2>
      <input
        type="email"
        class="form-control"
        name="email"
        placeholder="Email"
        required
        autofocus></input>
      <input
        type="password"
        class="form-control"
        name="password"
        placeholder="Password"></input>
      <button class="btn btn-lg btn-primary btn-block">Ingresar</button>
    </form>
  </div>
</template>

<style scoped>
.wrapper {
  margin: 80px;
}

.signin-logo {
  max-width: 300px;
  margin-bottom: 30px;
}

.form-singin {
  max-width: 380px;
  margin: 0 auto;
  background-color: #fff;
  padding: 15px 40px 50px;
  border: 1px solid #e5e5e5;
  border-radius: 10px;
}

.form-singin-heading {
  margin-bottom: 20px;
}

.form-control {
  margin-bottom: 10px;
}

</style>

<script>
export default {

}
</script>
