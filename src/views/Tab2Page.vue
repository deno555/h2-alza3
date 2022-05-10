<template>
  <ion-page>
    <ion-content>
      <ion-header>
        <!-- import <AHeader /> component -->
      </ion-header>
        <AADetailsPage />
    </ion-content>
  </ion-page>  
</template>

<script lang="ts">
  import AADetailsPage from '@/plugins/detailPage/view/AADetailsPage.vue';
  import { IonPage, IonContent, IonHeader} from '@ionic/vue';
  // import AHeader \import header2 from '@/plugins/global_component/AHeader.vue'\ 

  export default{
      components: {AADetailsPage, IonPage, IonContent, IonHeader} // pridat 'AHeader'
  }
</script> 