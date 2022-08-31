<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title>第五空间</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content :fullscreen="true">
      <ion-header collapse="condense">
        <ion-toolbar>
          <ion-title size="large">Tab 2</ion-title>
        </ion-toolbar>
      </ion-header>
      <iframe src="https://www4.cbox.ws/box/?boxid=4327572&amp;boxtag=Cf5HyA&amp;tid=1&amp;tkey=ce16b6434b5e5b3b" marginwidth="0" marginheight="0" scrolling="auto" width="100%" height="100%" frameborder="0"></iframe>
      
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';

export default defineComponent({
  name: 'Tab2Page',
  components: { IonHeader, IonToolbar, IonTitle, IonContent, IonPage }
});
</script>
