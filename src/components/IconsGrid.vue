<template>
  <section class="features-icons bg-light text-center">
    <div class="container">
      <div class="row">
        <div class="col-lg-4">
          <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
            <div class="features-icons-icon d-flex">
              <i class="icon-screen-desktop m-auto text-primary"></i>
            </div>
            <h3>Completo</h3>
            <p class="lead mb-0">
              Cubrimos desde la gestión de personal de seguridad y limpieza
              hasta la autogestión de facturación, pagos y servicios.
            </p>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="features-icons-item mx-auto mb-5 mb-lg-0 mb-lg-3">
            <div class="features-icons-icon d-flex">
              <i class="icon-layers m-auto text-primary"></i>
            </div>
            <h3>Intuitivo</h3>
            <p class="lead mb-0">
              Fácil de usar, nuestros usuarios pueden acceder a la plataforma
              web o desde las aplicaciones móviles.
            </p>
          </div>
        </div>
        <div class="col-lg-4">
          <div class="features-icons-item mx-auto mb-0 mb-lg-3">
            <div class="features-icons-icon d-flex">
              <i class="icon-check m-auto text-primary"></i>
            </div>
            <h3>Personalizado</h3>
            <p class="lead mb-0">
              Contamos con varios planes cada uno con diferentes
              funcionalidades, ajustados a cubrir las necesidades de nuestros
              usuarios.
            </p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({})
export default class IconsGrid extends Vue {}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
