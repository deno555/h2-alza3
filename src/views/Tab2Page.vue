<template>
  <ion-page>
    <ion-content>
      <DetailsPage />
    </ion-content>
  </ion-page>
</template>

<script lang = 'ts'>
import { defineComponent } from 'vue';
import DetailsPage from '@/plugins/detailPage/view/DetailsPage.vue'
//import ExploreContainer from '@/components/ExploreContainer.vue';
import { IonPage, IonContent } from '@ionic/vue';


export default defineComponent({
  name: 'Tab2Page',
  components: {DetailsPage, IonPage, IonContent}
});

</script>
