<template>
  <ion-page>
    <ion-content>
      <DetailsPage />
    </ion-content>
  </ion-page>  
</template>

<script>
  import DetailsPage from '@/plugins/detailPage/view/detailsPage.vue'
  import { IonPage, IonContent} from '@ionic/vue';
  //import contentShow from '@/plugins/detailPage/component/contentShow.vue'

  export default{
      components: {DetailsPage, IonPage, IonContent}
  }
</script> 