<template>
  <ion-page>
    <page-header></page-header>

    <ion-content :fullscreen="true">
      <ion-grid class="ion-padding">
        <ion-row class="ion-align-items-center">
          <ion-col class="ion-text-center" size="6">
            <h1 class="font-weight-bold ion-text-capitalize">
              <ion-text color="primary">introducing dema planner</ion-text>
            </h1>
            <p>
              Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aut
              iusto deserunt earum, consequuntur maiores delectus harum
              voluptate temporibus, adipisci sunt optio enim suscipit dolor odit
              reiciendis non tempore beatae aperiam?
            </p>
            <ion-button shape="round" class="ion-text-capitalize custom-btn">
              Learn more
            </ion-button>
          </ion-col>
          <ion-col size="6">
            <img
              :src="require('../assets/images/food-delivery.png')"
              class="intro-img"
            />
          </ion-col>
        </ion-row>

        <ion-row class="ion-text-center">
          <ion-col size="12">
            <h2 class="font-weight-bold">
              <ion-text class="subtitle" color="primary">Features</ion-text>
            </h2>
          </ion-col>
          <ion-col size="4">
            <img
              :src="require('../assets/images/exercise.png')"
              class="feature-img"
            />
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro
              sapiente incidunt fugiat distinctio fugit laborum ullam ducimus
              saepe, nam voluptatem voluptas reiciendis eveniet minus doloribus
              esse quasi pariatur consequatur. Repellendus.
            </p>
          </ion-col>
          <ion-col size="4">
            <img
              :src="require('../assets/images/camera.png')"
              class="feature-img"
            />
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro
              sapiente incidunt fugiat distinctio fugit laborum ullam ducimus
              saepe, nam voluptatem voluptas reiciendis eveniet minus doloribus
              esse quasi pariatur consequatur. Repellendus.
            </p>
          </ion-col>
          <ion-col size="4">
            <img
              :src="require('../assets/images/social-media.png')"
              class="feature-img"
            />
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Porro
              sapiente incidunt fugiat distinctio fugit laborum ullam ducimus
              saepe, nam voluptatem voluptas reiciendis eveniet minus doloribus
              esse quasi pariatur consequatur. Repellendus.
            </p>
          </ion-col>
        </ion-row>

        <ion-row class="ion-text-center">
          <ion-col size="12" class="ion-text-center">
            <img
              :src="require('../assets/images/app.png')"
              class="banner-img"
            />
          </ion-col>
          <ion-col size="12" class="ion-text-center">
            <div class="intro-video">
              <img
                class="play-img"
                :src="require('../assets/images/play.png')"
              />
            </div>
          </ion-col>
        </ion-row>
      </ion-grid>

      <page-footer></page-footer>
    </ion-content>
  </ion-page>
</template>

<script>
import {
  IonPage,
  IonContent,
  IonButton,
  IonGrid,
  IonRow,
  IonCol,
  IonText,
} from "@ionic/vue";
import PageHeader from "../components/PageHeader.vue";
import PageFooter from "../components/PageFooter.vue";

export default {
  name: "HomePage",
  components: {
    IonPage,
    IonContent,
    IonButton,
    IonGrid,
    IonRow,
    IonCol,
    IonText,
    PageHeader,
    PageFooter,
  },
};
</script>

<style scoped></style>
