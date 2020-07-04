<template>
  <div class='container'>
    <nav class='navbar navbar-expand-lg navbar-light bg-light'>
      <a class='navbar-brand' href='#'>Início</a>
      <ul class='navbar-nav mr-auto'>
        <li class='nav-item'>
          <a class='nav-link' href='NavBar.vue'>Listar posts</a>
        </li>
        <li class='nav-item'>
          <a class='nav-link' href='NavBar.vue'>Criar post</a>
        </li>
      </ul>
      <logout-bar v-if='loggedIn'></logout-bar>
      <login-getter v-else ></login-getter>
    </nav>
  </div>
</template>

<script>
import LoginGetter from './LoginGetter.vue';
import LogoutBar from './LogoutBar.vue';

export default {
  name: 'NavBar',
  components: {
    LogoutBar,
    LoginGetter,
  },
  data() {
    return {
      loggedIn: true,
    };
  },
};
</script>

<style scoped>

</style>
