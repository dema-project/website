<template>
  <ion-page>
    <ion-header :translucent="true" class="ion-no-border b">
      <ion-toolbar>
        <ion-title size="large">Title</ion-title>

        <ion-buttons slot="end" :collapse="true">
          <ion-button class="ion-text-capitalize">Button</ion-button>
          <ion-button class="ion-text-capitalize">Button</ion-button>
          <ion-button
            shape="round"
            class="ion-text-capitalize"
            color="primary"
            fill="solid"
            >Button</ion-button
          >
        </ion-buttons>
      </ion-toolbar>
    </ion-header>

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

      <ion-footer>
        <div class="b">
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
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonContent,
  IonHeader,
  IonPage,
  IonTitle,
  IonToolbar,
  IonButtons,
  IonButton,
  IonGrid,
  IonRow,
  IonCol,
} from "@ionic/vue";

export default {
  name: "HomePage",
  components: {
    IonContent,
    IonHeader,
    IonPage,
    IonTitle,
    IonToolbar,
    IonButtons,
    IonButton,
    IonGrid,
    IonRow,
    IonCol,
  },
};
</script>

<style scoped></style>
