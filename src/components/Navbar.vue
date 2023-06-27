<template>
  <div>
    <b-navbar toggleable="lg" type="dark" fixed="top">
      <router-link to="/">
        <img
            src="../assets/logo.png" alt="logo"
        />
      </router-link>

      <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

      <b-collapse id="nav-collapse" is-nav>
        <b-navbar-nav>
          <router-link to="/about" class="nav-link">Quem Somos?</router-link>
          <router-link to="/projetos" class="nav-link">Projetos</router-link>
          <router-link to="/contato" class="nav-link">Contato</router-link>    
        </b-navbar-nav>

        <b-navbar-nav class="ml-auto">
          <b-nav-form>
            <b-form-input
              size="sm"
              class="mr-sm-2"
              placeholder="Pesquisar"
            ></b-form-input>
          </b-nav-form>
        </b-navbar-nav>
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
/* eslint-disable */
export default {
    name: "Navbar",
};
</script>

<style scoped>
img {
    width: 50px;
    height: 50px;
    margin-left: 30px;
}
.navbar {
    background-color: gray;
}
.navbar-nav .nav-link {
    color: #fff;
    font-weight: bold;
}
.navbar-nav .nav-link:hover {
    color: #193c5f;
}

.navbar-collapse {
  display: flex;
  justify-content: flex-end;
  margin-right: 30px;
}
</style>
```
