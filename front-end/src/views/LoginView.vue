<template>
<div>
  <h2>Login</h2>

  <form @submit.prevent="Login">
  
    <input type="text" placeholder="Seu email">
    <input type="password" placeholder="Sua Senha">
    <button type="submit">Login</button>

  </form>
  
</div>
  
</template>

<script setup>

function Login(){
  alert('Olá')
}

</script>


<style>

</style>
