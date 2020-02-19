<template>
<div class="bg-green-500 min-h-screen">
  <NavBar />
  <router-view />
</div>
</template>

<script>
import NavBar from './components/NavBar'

export default {
  name:'App',
  components: {
    NavBar
  }
}
</script>
