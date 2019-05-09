<template>
  <div>
    <nav-bar></nav-bar>
    <login></login>
  </div>
</template>

<script>
import NavBar from '@/components/NavBar'
import Login from '@/components/Login'

export default {
  components: {
    NavBar,
    Login
  }
}
</script>
