<template>
  <nav class="navbar navbar-light bg-light static-top">
    <div class="container">
      <a class="navbar-brand" href="#">Nudoor</a>
      <a class="btn btn-primary" href="#">Registro</a>
    </div>
  </nav>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class NavigationBar extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
