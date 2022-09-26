<template>
  <ion-page>
    <page-header></page-header>

    <ion-content :fullscreen="true">
      <ion-grid class="b ion-padding">
        <ion-row class="b ion-align-items-end">
          <ion-col class="b ion-text-center" size="6">
            <h1>Title</h1>
            <p>Subtitle</p>
            <ion-button shape="round" class="ion-text-capitalize custom-btn"
              >Button</ion-button
            >
          </ion-col>
          <ion-col class="b" size="6">
            <img class="b home-img" />
          </ion-col>
        </ion-row>

        <ion-row class="b ion-text-center">
          <ion-col size="12" class="b">
            <ion-title>
              <ion-text color="primary" class="ion-text-underline"
                >Subtitle</ion-text
              >
            </ion-title>
          </ion-col>
          <ion-col size="4" class="b">
            <img class="b home-img" />
            <p>Some text</p>
          </ion-col>
          <ion-col size="4" class="b">
            <img class="b home-img" />
            <p>Some text</p>
          </ion-col>
          <ion-col size="4" class="b">
            <img class="b home-img" />
            <p>Some text</p>
          </ion-col>
        </ion-row>

        <ion-row class="b ion-text-center">
          <ion-col size="12" class="ion-text-center">
            <img class="b banner-img" />
          </ion-col>
          <ion-col size="12" class="ion-text-center">
            <div class="b intro-video"></div>
          </ion-col>
        </ion-row>
      </ion-grid>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonContent,
  IonPage,
  IonTitle,
  IonToolbar,
  IonButtons,
  IonButton,
  IonGrid,
  IonRow,
  IonCol,
  IonText,
  IonFooter,
} from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";

export default {
  name: "HomePage",
  components: {
    IonContent,
    IonPage,
    IonTitle,
    IonToolbar,
    IonButtons,
    IonButton,
    IonGrid,
    IonRow,
    IonCol,
    IonText,
    IonFooter,
    PageHeader,
  },
};
</script>

<style scoped></style>
