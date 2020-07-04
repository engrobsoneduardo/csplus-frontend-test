<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <a class="navbar-brand" href="#">Início</a>
      <ul class="navbar-nav mr-auto">
        <li class="nav-item">
          <a class="nav-link" href="NavBar.vue">Listar posts</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="NavBar.vue">Criar post</a>
        </li>
      </ul>
      <ul class="navbar-nav ml-auto">
        <li class="nav-item">
          <a class="nav-link" href="NavBar.vue">Logout</a>
        </li>
      </ul>
    </nav>
    <a class="btn btn-primary">teste botão</a>
  </div>
</template>

<script>
export default {
  name: 'NavBar',
};
</script>

<style scoped>

</style>
