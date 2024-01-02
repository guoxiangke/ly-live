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
      <div  class="button-17" style="position: absolute;top: 500px;right: 10px; border-radius: 50%;max-width: 50px;">
          <a href="https://app.729ly.net" rel="noreferrer" target="_blank">
            <img src="/assets/icon/lylogo.png"  style="border-radius: 50%;max-width: 50px;" alt="良友随身听" title="良友随身听" />
          </a>
      </div>
      <br/>
      <br/>
      <br/>
      <audio style="width: 100%;" controls src="https://listen.729ly.net:8001/ly729_a"></audio>
    </ion-content>
  </ion-page>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent,
  IonFab, 
  IonFabButton,
  IonIcon,
  IonImg,
} from '@ionic/vue';

export default  defineComponent({
  name: 'Tab1Page',
  components: {  IonHeader, IonToolbar, IonTitle, IonContent, IonPage },
  data() {
    let urls = ['https://ly729.out.airtime.pro/ly729_a','https://ly729.out.airtime.pro/ly729_b','https://listen.729ly.net:8001/ly729_a']
    urls = urls.sort(() => Math.random() - 0.5);
    return {
      urls
    }
  }
});


</script>
