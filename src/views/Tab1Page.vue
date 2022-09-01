<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>同行频道</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">同行频道</ion-title>
        </ion-toolbar>
      </ion-header>
      <div style="text-align: center; padding: 4em;">
        <!-- https://ly729.airtime.pro/api/live-info -->
        <audio controls="controls" autoplay preload="true">
          <source src="https://ly729.out.airtime.pro/ly729_a" type="audio/mpeg">
          <source src="https://ly729.out.airtime.pro/ly729_b" type="audio/mp3">
          <source src="https://listen.729ly.net:8001/ly729_a" type="audio/mp3">
        </audio>
      </div>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: {  IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
