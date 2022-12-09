<template>
  <ion-menu content-id="main-content">
    <ion-header>
      <ion-toolbar color="tertiary">
        <ion-title>Tus cuentos</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">CREA TU PROPIO CUENTO</ion-content>
  </ion-menu>
  <ion-page id="main-content">
    <ion-header>
      <ion-toolbar>
        <ion-buttons slot="start">
          <ion-menu-button></ion-menu-button>
        </ion-buttons>
        <ion-title>Cuentos de animales</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      La hormiguita voladora
      <br>
      <br>
      <br>
      Érase una vez una tortuga que vivía muy cerca de donde un águila tenía su nido.

Cada mañana observaba a la reina de las aves y se moría de envidia al verla volar.

– ¡Qué suerte tiene el águila! Mientras yo me desplazo por tierra y tardo horas en llegar a cualquier lugar, ella puede ir de un sitio a otro en cuestión de segundos ¡Cuánto me gustaría tener sus magníficas alas!

El águila, desde arriba, se daba cuenta de que una tortuga siempre la seguía con la mirada, así que un día se posó a su lado.

– ¡Hola, amiga tortuga! Todos los días te quedas pasmada contemplando lo que hago ¿Puedes explicarme a qué se debe tanto interés?

– Perdona, espero no haberte parecido indiscreta… Es tan sólo que me encanta verte volar ¡Ay, ojalá yo fuera como tú!

El águila la miró con dulzura e intentó animarla.

– Bueno, es cierto que yo puedo volar, pero tú tienes otras ventajas; ese caparazón, por ejemplo, te protege de los enemigos mientras que yo voy a cuerpo descubierto.

La tortuga respondió con poco convencimiento.

– Si tú lo dices… Verás, no es que me queje de mi caparazón pero no se puede comparar con volar ¡Tiene que ser alucinante contemplar el paisaje desde el cielo, subir hasta las nubes, sentir el aire fresco en la cara y escuchar de cerca el sonido del viento justo antes de las tormentas!

La tortuga tenía los ojos cerrados mientras imaginaba todos esos placeres, pero de repente los abrió y en su cara se dibujó una enorme sonrisa ¡Ya sabía cómo cumplir su gran sueño!

– Escucha, amiga águila ¡se me ocurre una idea!  ¿Qué te parece si me enseñas a volar?

El águila no daba crédito a lo que estaba escuchando.
El águila bajó en picado y comprobó el estado lamentable en que su amiga había quedado. El caparazón estaba lleno de grietas, tenía las cuatro patitas rotas y su cara ya no era verde, sino morada. Había sobrevivido de milagro pero tardaría meses en recuperarse de las heridas.

El águila la incorporó y se puso muy seria con ella.

– ¡Traté de avisarte del peligro y no me hiciste caso, así que aquí tienes el resultado de tu estúpida idea!

La tortuga, muy dolorida, admitió su error.

– ¡Ay, ay, tienes razón, amiga mía!  Me dejé llevar por la absurda ilusión de que las tortugas también podíamos volar y me equivoqué. Lamento no haberte escuchado.

Así fue cómo la tortuga comprendió que era tortuga y no ave, y que como todos los seres vivos, tenía sus propias limitaciones. Al menos el porrazo le sirvió de escarmiento y, a partir de ese día, aprendió a escuchar los buenos consejos de sus amigos cada vez que se le pasaba por la cabeza cometer alguna nueva locura.
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
  import {
    IonButtons,
    IonContent,
    IonHeader,
    IonMenu,
    IonMenuButton,
    IonPage,
    IonTitle,
    IonToolbar
  } from '@ionic/vue';
  import { defineComponent } from 'vue';

  export default defineComponent({
    components: {
      IonButtons,
      IonContent,
      IonHeader,
      IonMenu,
      IonMenuButton,
      IonPage,
      IonTitle,
      IonToolbar
    },
  });
</script>

<style scoped>
  ion-menu::part(backdrop) {
    background-color: rgba(99, 27, 243, 0.5);
  }

  ion-menu::part(container) {
    border-radius: 0 20px 20px 0;

    box-shadow: 4px 0px 16px rgba(240, 245, 110, 0.18);
  }
  ion-content::part(container){
    box-shadow: 4px 0px 16px rgba(240, 245, 110, 0.18);
  }
</style>