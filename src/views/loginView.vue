<template>
  <div class="login">
    <h1>LOGIN</h1>
    <div class="inputl">
      <div class="inputl1"><input type="text" placeholder="Nome/E-mail" /></div>
      <div class="inputl2"><input type="text" placeholder="Senha" /></div>
      <div class="buttonl"><button>Enviar.</button></div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .login {
    display: flex;

    color: rgb(0, 0, 0);
    text-align: center;
    flex-direction: column;
    margin-left: 40%;
    font-size: 30px;
    margin-right: 20%;
    border: 1px solid white;
    background-color: rgba(255, 255, 255, 0.664);
    border-radius: 15px;
    margin-top: 5%;
    margin-bottom: 20%;
  }
  .inputl {
    display: flex;
    flex-direction: column;
  }
  .inputl1 {
    margin-top: 4%;
  }
  .inputl2 {
    margin-top: 4%;
  }
}
</style>
