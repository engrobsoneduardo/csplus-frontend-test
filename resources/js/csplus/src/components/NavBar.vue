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
      <login-getter></login-getter>
    </nav>
    <a class="btn btn-primary">teste botão</a>
  </div>
</template>

<script>
import LoginGetter from './LoginGetter.vue';

export default {
  name: 'NavBar',
  components: { LoginGetter },
  data() {
    return {
      loggedIn: false,
    };
  },
};
</script>

<style scoped>

</style>
