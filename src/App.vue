<template>
  <navigation-bar />
  <master-head />
  <icons-grid />
  <images-showcase />
  <testimonials />
  <call-to-action />
  <custom-footer />
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import NavigationBar from "./components/NavigationBar.vue";
import MasterHead from "./components/MasterHead.vue";
import IconsGrid from "./components/IconsGrid.vue";
import ImagesShowcase from "./components/ImagesShowcase.vue";
import Testimonials from "./components/Testimonials.vue";
import CustomFooter from "./components/Footer.vue";
import CallToAction from "./components/CallToAction.vue";

@Options({
  components: {
    NavigationBar,
    MasterHead,
    IconsGrid,
    ImagesShowcase,
    Testimonials,
    CallToAction,
    CustomFooter
  }
})
export default class App extends Vue {}
</script>
