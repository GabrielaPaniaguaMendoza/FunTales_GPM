<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>Fun tales</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2</ion-title>
        </ion-toolbar>
      </ion-header>
      <div>
      <ion-searchbar :search-icon="searchCircle" placeholder="Buscar"></ion-searchbar>
      </div>
      
      <ExploreContainer name="Tab 2 page" />
    </ion-content>
  <ion-card color="primary">
  <ion-card-header>
    <ion-card-title>Card Title</ion-card-title>
    <ion-card-subtitle>Card Subtitle</ion-card-subtitle>
  </ion-card-header>
    <ion-card-content>
      <ion-list>
        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://i.pinimg.com/564x/23/3d/16/233d160a470f9f58771753179ffedd4e.jpg" />
          </ion-thumbnail>
          <ion-label>Cuentos de animales</ion-label>
        </ion-item>

        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://i.pinimg.com/564x/c4/4e/84/c44e840d3628aa87bfb4d7f6d235a6c8.jpg" />
          </ion-thumbnail>
          <ion-label>Cuentos Misterio</ion-label>
        </ion-item>

        <ion-item>
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://i.pinimg.com/564x/e5/85/cf/e585cfb2454f3cd8a172c143523269ea.jpg" />
          </ion-thumbnail>
          <ion-label>Cuentos historicos</ion-label>
        </ion-item>

        <ion-item lines="none">
          <ion-thumbnail slot="start">
            <img alt="Silhouette of mountains" src="https://i.pinimg.com/564x/4a/a4/79/4aa479031a65eb6c4f7b60fb472a84b7.jpg" />
          </ion-thumbnail>
          <ion-label>Cuentos comicos</ion-label>
        </ion-item>

       

        
      </ion-list>
    </ion-card-content>
  </ion-card>

  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default defineComponent({
  name: 'Tab2Page',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
