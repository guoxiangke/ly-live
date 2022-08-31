<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>节目时间</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 3</ion-title>
        </ion-toolbar>
      </ion-header>
      <iframe src="https://ly729.airtime.pro/embed/weekly-program" 
        scrolling="no"
        width="100%" 
        height="100%"
        frameborder="0"

        ></iframe>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab3Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
