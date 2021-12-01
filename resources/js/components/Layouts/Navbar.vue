<template>
<div>
  <b-navbar toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#">NavBar</b-navbar-brand>
    <router-link to="/" class="nav-item nav-link">Home</router-link>
    <router-link to="/add" class="nav-item nav-link">Add Book</router-link>
  </b-navbar>
  <router-view></router-view>
</div>
</template>