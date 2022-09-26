<template>
  <ion-page>
    <page-header></page-header>

    <h1>Contact page</h1>
  </ion-page>
</template>

<script>
import { IonPage } from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";

export default {
  name: "ContactPage",
  components: {
    IonPage,
    PageHeader,
  },
};
</script>

<style scoped></style>
