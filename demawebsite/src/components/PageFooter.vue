<template>
  <ion-footer>
    <div class="ion-text-center footer-bg">
      <ion-grid>
        <ion-row class="ion-align-items-center ion-padding-vertical">
          <ion-col size="6">
            <h2 class="font-weight-bold">
              <ion-text color="light">Ready to get started?</ion-text>
            </h2>
          </ion-col>
          <ion-col size="6">
            <ion-item lines="none" color="transparent">
              <ion-icon slot="start" :icon="person"></ion-icon>
              <ion-label position="floating">Name</ion-label>
              <ion-input clear-input type="text"></ion-input>
            </ion-item>
            <ion-item
              lines="none"
              color="transparent"
              class="ion-margin-vertical"
            >
              <ion-icon slot="start" :icon="mail"></ion-icon>
              <ion-label position="floating">Email</ion-label>
              <ion-input clear-input type="email"></ion-input>
            </ion-item>
            <ion-button
              shape="round"
              expand="block"
              color="primary"
              class="ion-text-capitalize"
            >
              Download app
            </ion-button>
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
  IonInput,
  IonItem,
  IonLabel,
  IonButton,
  IonIcon,
  IonText,
} from "@ionic/vue";
import { person, mail } from "ionicons/icons";

export default {
  name: "PageFooter",
  data() {
    return {
      person,
      mail,
    };
  },
  components: {
    IonFooter,
    IonGrid,
    IonRow,
    IonCol,
    IonToolbar,
    IonButtons,
    IonInput,
    IonItem,
    IonLabel,
    IonButton,
    IonIcon,
    IonText,
  },
};
</script>

<style scoped></style>
