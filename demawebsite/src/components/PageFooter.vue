<template>
  <ion-footer class="b">
    <div>
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
    <ion-toolbar>
      <ion-buttons>
        <ion-button class="ion-text-capitalize">About</ion-button>
        <ion-button class="ion-text-capitalize">Contact</ion-button>
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
