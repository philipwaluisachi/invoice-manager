<template>
  <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container-fluid">
    <a class="navbar-brand" href="#"><router-link to="/">INVOICE APP</router-link></a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link">
            <router-link to="/">Invoices</router-link>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link">
            <router-link to="/create-invoice">Create Invoice</router-link>
          </a>
        </li>
        <li class="nav-item">
          <a class="nav-link">
            <router-link to="/edit/22">Edit Contact</router-link>
          </a>
        </li>
      </ul>
    </div>
  </div>
</nav>
</template>

<script>
  export default {
    name: "Nav",
  }
</script>

<style scoped>
  nav ul li a, navbar-brand{
    text-decoration: none;
  }
</style>
