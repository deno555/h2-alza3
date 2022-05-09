<template>
  <ion-page>
    <ion-header>
      <ion-toolbar>
        <ion-title class="ion-text-center">Stážisti</ion-title>
        <ion-button><ion-icon name="options-outline"></ion-icon></ion-button>
      </ion-toolbar>
    </ion-header>
    <ion-content>

      <div class="nobull" v-for="(i) in card" :key="i.cardTitle">
          <ion-card>
            <ion-card-header>
              <img width="85" class="imgs" src="https://cdn.discordapp.com/attachments/768503373363806218/970768614942732388/unknown.png">
              <img width="25" top="100px" class="imgs" src="https://cdn.discordapp.com/attachments/768503373363806218/970968283715096586/unknown.png">
            </ion-card-header>

            <ion-card-content>
              <p>Impostor</p>
              <p>Sus</p>
              <p>C#</p>
              <p>Tvoju mamu</p>
              <p>Vesmir</p>
            </ion-card-content>
          </ion-card> 
      </div>

    <ion-button @click="addCard()">Test</ion-button>

    </ion-content>
  </ion-page>

</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent} from '@ionic/vue';

  export default  defineComponent({
    name: 'Tab1Page',
    components: {IonHeader, IonToolbar, IonTitle, IonContent, IonPage},

    data(){
      return{
        //veci ktore zoberem z backendu
        name:'',
        job:'',
        skillsInJob:'',
        money:'',
        city:'',
        //veci ktore vytvorim tu
        card:[
          {cardID:0},
          {cardID:1},
          {cardID:2},
          {cardID:3},
          {cardID:4},
          {cardID:5},
          ]
      };
    },

    methods:{
        // addName(){
        //   this.card.push({
        //     nameText:this.name,
        //   }),
        //   this.name=''
        // },

        // addJob(){
        //   this.card.push({
        //     jobText:this.job,
        //   }),
        //   this.job=''
        // },

        // addSkill(){
        //   this.card.push({
        //     skillText:this.skillsInJob,
        //   }),
        //   this.skillsInJob=''
        // },

        // addMoney(){
        //   this.card.push({
        //     moneyNum:this.money,
        //   }),
        //   this.money=''
        // },

        // addCity(){
        //   this.card.push({
        //     cityText:this.city,
        //   }),
        //   this.city=''
        // },

        addCard(cardID){
          this.card.push({
            cardID:cardID+1
          })
        },

      }
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

  .button{
    width: 10000px;
    height: 10000px;
  }

  .nobull {
  list-style-type:"";
 }

</style>