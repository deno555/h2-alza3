<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="header">Stážisti</ion-title>
      </ion-toolbar>
    </ion-header>
    <ion-content>
        <Profile />

        
    </ion-content>
  </ion-page>

</template>

<style>
  .header{
        position:fixed;
    }
</style>

<script>
    import {IonHeader, IonToolbar, IonTitle, IonContent} from '@ionic/vue';
    import Profile from '@/plugins/kokot/component/card.vue';

    export default {
        components: {
            IonHeader, 
            IonToolbar, 
            IonTitle, 
            IonContent,
            Profile,
        },

    }
</script>