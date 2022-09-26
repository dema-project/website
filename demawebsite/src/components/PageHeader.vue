<template>
  <ion-header :translucent="true" class="ion-no-border">
    <ion-toolbar class="ion-padding-horizontal">
      <ion-title size="large" class="ion-text-capitalize font-weight-bold">
        <ion-text color="primary">Dema Planner</ion-text>
      </ion-title>

      <ion-buttons slot="end" :collapse="true">
        <ion-button
          router-link="/about"
          class="ion-text-capitalize nav-button"
          shape="round"
        >
          About
        </ion-button>
        <ion-button
          router-link="/contact"
          class="ion-text-capitalize"
          shape="round"
        >
          Contact
        </ion-button>
        <!-- <ion-button
            shape="round"
            class="ion-text-capitalize custom-btn"
            color="primary"
            fill="solid"
          >
            Register
          </ion-button> -->
      </ion-buttons>
    </ion-toolbar>
  </ion-header>
</template>

<script>
import {
  IonHeader,
  IonToolbar,
  IonTitle,
  IonButtons,
  IonButton,
  IonText,
} from "@ionic/vue";

export default {
  name: "PageHeader",
  components: {
    IonHeader,
    IonToolbar,
    IonTitle,
    IonButtons,
    IonButton,
    IonText,
  },
};
</script>

<style scoped></style>
