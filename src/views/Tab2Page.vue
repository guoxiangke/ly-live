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
          <ion-title size="large">第五空间</ion-title>
        </ion-toolbar>
      </ion-header>
      <iframe src="https://www4.cbox.ws/box/?boxid=4327572&amp;boxtag=Cf5HyA&amp;tid=1&amp;tkey=ce16b6434b5e5b3b" marginwidth="0" marginheight="0" scrolling="auto" width="100%" height="100%" frameborder="0"></iframe>
      
      <div style="margin:2em">
        <p>发言须知</p>
          <ul>
            <li>请勿张贴个人通讯资料、广告、不雅内容、攻击、造谣、诽谤、灌水等的帖子，本版管理人员有权删除任何不合宜的内容。</li>
            <li>鼓励原创，避免重复发帖，切勿张贴未获授权转载的图片或文字，以免侵犯别人的版权。</li>
            <li>最终解释权和决定权属良友电台所有。</li>
          </ul>

          <p>发言步骤</p> 

          <ul>
            <li>首次发言时，输入名称后，按右方的“登录”按钮，然后输入密码，再多输入一次密码，最后按“注册”按钮，系统便会把你的名称记录下来。</li>
            <li>以后你在同一台电脑或手机发言，名称会自动记录下来。如你在其他电脑或手机发言，便需要再次输入名称和密码，方可发言。</li>
          </ul>
          

          
      </div>
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
