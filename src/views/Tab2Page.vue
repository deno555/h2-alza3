<template>
  <ion-page>
    <ion-content>
      <ion-header>
        <!-- import <AHeader /> component -->
      </ion-header>
        <DetailsPage />
    </ion-content>
  </ion-page>  
</template>

<script lang="ts">
  import DetailsPage from '@/plugins/detailPage/view/DetailsPage.vue';
  import { IonPage, IonContent, IonHeader} from '@ionic/vue';
  // import AHeader \import header2 from '@/plugins/global_component/AHeader.vue'\ 

  export default{
      components: {DetailsPage, IonPage, IonContent, IonHeader} // pridat 'AHeader'
  }
</script> 