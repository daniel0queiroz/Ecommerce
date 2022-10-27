<template>
  <div class="sticky-top">
    <nav class="navbar navbar-expand-lg bg-light bg-white shadow">
  <div class="container">
    <a class="navbar-brand" href="#">
      <img src="/images/carne-bovina.jpg.webp" class="logo-img" alt="">
    </a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <NuxtLink to="/" class="nav-link ">Página Inicial</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/about" class="nav-link ">Sobre Nós</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/contact" class="nav-link ">Contato</NuxtLink>
        </li>
        <li class="nav-item">
          <NuxtLink to="/products" class="nav-link ">Produtos</NuxtLink>
        </li>
      
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item dropdown">
          <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
            Dropdown
          </a>
          <ul class="dropdown-menu">
            <li><a class="dropdown-item" href="#">Action</a></li>
            <li><a class="dropdown-item" href="#">Another action</a></li>
            <li><hr class="dropdown-divider"></li>
            <li><a class="dropdown-item" href="#">Something else here</a></li>
          </ul>
        </li>
        <li class="nav-item">
          <a class="nav-link disabled">Disabled</a>
        </li>
      </ul>
      <form class="d-flex" role="search">
        <input class="form-control me-2" type="search" placeholder="Search" aria-label="Search">
        <button class="btn btn-outline-success" type="submit">Search</button>
      </form>
    </div>
  </div>
</nav>
  </div>
</template>

<script>
export default {
    name: 'AppHeader'
}
</script>

<style>
.logo-img{
  width: 120px;
}
</style>
