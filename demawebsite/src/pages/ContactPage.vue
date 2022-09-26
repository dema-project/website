<template>
  <ion-page>
    <page-header></page-header>

    <ion-content :fullscreen="true">
      <h1>Contact page</h1>

      <page-footer></page-footer>
    </ion-content>
  </ion-page>
</template>

<script>
import { IonPage } from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";
import PageFooter from "../components/PageFooter.vue";

export default {
  name: "ContactPage",
  components: {
    IonPage,
    PageHeader,
    PageFooter,
  },
};
</script>

<style scoped></style>
