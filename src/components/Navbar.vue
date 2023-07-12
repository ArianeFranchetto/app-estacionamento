<template>

<nav class="navbar navbar-expand-lg bg-navbar bg-dark border-bottom border-bottom-dark" data-bs-theme="dark">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"> <img class="logo-home" src="../assets/logo.gif" id="logo"/></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNavDropdown">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page"><router-link to="/">Cadastro</router-link> </a>
        </li>
        <li class="nav-item">
          <a class="nav-link"><router-link to="/cadastro">Carros Cadastrados</router-link></a>
        </li>
      
        <li>
          <a class="nav-link dropdown-toggle" data-bs-toggle="dropdown" aria-expanded="false">
          
          </a>
          
        </li>
      </ul>
    </div>
  </div>
</nav>
    

</template>

<script>
export default {
    name: "Navbar"
}

</script>

<style>
.logo-home {
    border-radius: 50%;
    width: 60px;
}



</style>

