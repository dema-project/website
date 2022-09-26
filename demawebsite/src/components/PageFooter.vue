<template>
  <ion-footer class="b">
    <div class="ion-text-center">
      <ion-grid>
        <ion-row>
          <ion-col size="6">
            <h1>Some stuff</h1>
          </ion-col>
          <ion-col size="6">
            <h1>Some stuff</h1>
          </ion-col>
        </ion-row>
      </ion-grid>
    </div>

    <ion-toolbar color="primary">
      <ion-buttons>
        <ion-button shape="round" class="ion-text-capitalize nav-button">
          About
        </ion-button>
        <ion-button shape="round" class="ion-text-capitalize nav-button">
          Contact
        </ion-button>
      </ion-buttons>
    </ion-toolbar>
  </ion-footer>
</template>

<script>
import {
  IonFooter,
  IonGrid,
  IonRow,
  IonCol,
  IonToolbar,
  IonButtons,
  IonButton,
} from "@ionic/vue";

export default {
  name: "PageFooter",
  components: {
    IonFooter,
    IonGrid,
    IonRow,
    IonCol,
    IonToolbar,
    IonButtons,
    IonButton,
  },
};
</script>

<style scoped></style>
