<template>
  
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>¡Hola pequeñ@s! -BIENVENIDOS</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 1</ion-title>
        </ion-toolbar>
      </ion-header>
    
      <ExploreContainer name="Tab 1 page" />
    </ion-content>
    
    <ion-card>
  <img alt="Silhouette of mountains" src="https://i.pinimg.com/750x/e8/b5/8a/e8b58a7263525b738c0cf47d80d3acb8.jpg" />
  <ion-card-header>
    <ion-card-title>Fun Tales</ion-card-title>
    <ion-card-subtitle>Imaginemos juntos</ion-card-subtitle>
  </ion-card-header>

  <ion-card-content>
    vamos a conocer juntos este mundo lleno de aventuras. Imagina grandes historias.
  </ion-card-content>
</ion-card>

  </ion-page>

</template>


<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';
import ExploreContainer from '@/components/ExploreContainer.vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: { ExploreContainer, IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});


</script>

