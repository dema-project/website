<template>
  <ion-page>
    <!-- Header component -->
    <page-header></page-header>

    <ion-content :fullscreen="true">
      <ion-router-outlet />

      <!-- Footer component -->
      <page-footer></page-footer>
    </ion-content>
  </ion-page>
</template>

<script>
import { IonPage, IonContent, IonRouterOutlet } from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";
import PageFooter from "../components/PageFooter.vue";

export default {
  name: "HomeView",
  components: {
    PageHeader,
    IonPage,
    IonContent,
    PageFooter,
    IonRouterOutlet,
  },
};
</script>

<style scoped></style>
