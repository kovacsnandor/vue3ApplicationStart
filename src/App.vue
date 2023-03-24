
<template>
  <div class="container-fluid my-container">
    <nav>
      <RouterLink to="/">Home</RouterLink> | 
      <RouterLink to="/about">About</RouterLink>
    </nav>
    
    <RouterView />
  </div>
</template>

<script>
import { RouterLink, RouterView } from 'vue-router'
export default {

}
</script>

<style>

</style>

