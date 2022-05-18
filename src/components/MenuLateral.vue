<script>
import { RouterLink } from "vue-router";
export default {
  components: { RouterLink },
};
</script>
<template>
  <!-- <nav>
        <RouterLink to="/">Home</RouterLink>
        <RouterLink to="/about">About</RouterLink>
      </nav> -->
  <aside id="sidenav">
    <ul>
      <div class="todoli">
        <div>
          <li><RouterLink to="/">Início</RouterLink></li>
        </div>
        <div>
          <li><RouterLink to="/about">Sobre</RouterLink></li>
        </div>
        <div>
          <li><RouterLink to="/contato">Contato</RouterLink></li>
        </div>
        <div>
          <li><RouterLink to="/login">Login/Cadastro</RouterLink></li>
        </div>
      </div>
    </ul>
  </aside>
</template>
<style></style>
