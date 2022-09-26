<template>
  <ion-page>
    <page-header></page-header>
    <h1>About page</h1>
  </ion-page>
</template>

<script>
import { IonPage } from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";

export default {
  name: "AboutPage",
  components: {
    IonPage,
    PageHeader,
  },
};
</script>

<style scoped></style>
