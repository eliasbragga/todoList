<template>
  <div id="app">
    <v-app>
      <b-navbar toggleable="lg" type="dark" variant="info" >
        <b-navbar-brand href="#" >TodoList</b-navbar-brand>
        <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>
        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav>
            <b-nav-item to="/">Tarefas</b-nav-item>
            <b-nav-item to="/formulario">Formulario</b-nav-item>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </v-app>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "app",
};
</script>

<style>
</style>
