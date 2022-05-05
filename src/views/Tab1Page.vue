<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="ion-text-center">Stážisti</ion-title>
        <ion-button><ion-icon name="options-outline"></ion-icon></ion-button>
      </ion-toolbar>
    </ion-header>
    <ion-content>

      <ion-card>
        <ion-card-header>
          <img width="85" class="imgs" src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png">
          <img width="25" top="100px" class="imgs" src="https://cdn.discordapp.com/attachments/768503373363806218/970968283715096586/unknown.png">
          <ion-card-title>Impostor</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          <p>sus</p>
          <p>C#</p>
          <p>tvoju mamu</p>
          <p>vesmir</p>
        </ion-card-content>
      </ion-card>

     <ion-card>
        <ion-card-header>
          <ion-card-subtitle> <img src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png"></ion-card-subtitle>
          <ion-card-title>Crewmate 1</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          chcem peniaze
        </ion-card-content>
      </ion-card>

    <ion-card>
        <ion-card-header>
          <ion-card-subtitle> <img src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png"></ion-card-subtitle>
          <ion-card-title>Crewmate 2</ion-card-title>

        </ion-card-header>

        <ion-card-content>
          chcem peniaze
        </ion-card-content>
      </ion-card>

    <ion-card>
        <ion-card-header>
          <ion-card-subtitle> <img src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png"></ion-card-subtitle>
          <ion-card-title>Crewmate 3</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          chcem peniaze
        </ion-card-content>
      </ion-card>

      <ion-card>
        <ion-card-header>
          <ion-card-subtitle><img src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png"></ion-card-subtitle>
          <ion-card-title>Crewmate 4</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          chcem peniaze
        </ion-card-content>
      </ion-card>

      <ion-card>
        <ion-card-header>
          <ion-card-subtitle> <img src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png"></ion-card-subtitle>
          <ion-card-title>Crewmate 5</ion-card-title>
        </ion-card-header>

        <ion-card-content>
          chcem peniaze
        </ion-card-content>
      </ion-card>

    </ion-content>
  </ion-page>

</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent} from '@ionic/vue';

  export default  defineComponent({
    name: 'Tab1Page',
    components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage}
    })

</script>

<style>
  ion-card{
    width: 40%;
    display: inline-block;
    height:270px;
    left:15px;
  };

  ion-header{
    height:1  px;
  };

  .imgs{
    display: inline-block;
  };

</style>