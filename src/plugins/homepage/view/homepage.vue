<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="ion-text-center">Stážisti</ion-title>
        <ion-button><ion-icon name="options-outline"></ion-icon></ion-button>
      </ion-toolbar>
    </ion-header>
    <ion-content>

    <ion-button @click="addCard()">Test</ion-button>

    </ion-content>
  </ion-page>

</template>

<script>
    import {IonHeader, IonToolbar, IonTitle, IonContent} from '@ionic/vue';
    import { defineComponent } from '@vue/runtime-core';

    export default defineComponent({
        components: {IonHeader, IonToolbar, IonTitle, IonContent},
    })
</script>
