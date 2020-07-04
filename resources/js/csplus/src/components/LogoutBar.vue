<template>
  <ul class='navbar-nav ml-auto'>
  <li class='nav-item'>
    <a class='btn btn-danger' href='NavBar.vue' onclick='logout'>Sair</a>
  </li>
  </ul>
</template>

<script>

export default {
  name: 'LogoutBar.vue',
  methods: {
    logout() {
      /* Matheus!
       * Essa é a linha em que eu disse que estou tendo problema.
       * Ela precisa acessar uma variável do componente pai.
       * Entretanto no navegador dá um erro (não é warning) de que eu estou importando
       * o NavBar sem instanciar. Se eu removo o import, o erro é de que estou usando o
       * componente sem importar.
       */
      //NavBar.data().loggedIn = false;
    },
  },
};
</script>

<style scoped>

</style>
