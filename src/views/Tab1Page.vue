<template>
    <Homepage/>
</template>

<script lang="ts">
  import { defineComponent } from 'vue';
  import Homepage from '@/plugins/homepage/view/homepage.vue';

  export default  defineComponent({
    name: 'Tab1Page',
    components:{
      Homepage
    },

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
          ],
        cardName:[
          {names:"Impostor"},
          {names:"Crewmate1"},
          {names:"Crewmate2"},
          {names:"Crewmate3"},
          {names:"Crewmate4"},
          {names:"Crewmate5"},
          ],
      };
    },

    methods:{
      addCard(cardID:number){
        this.card.push({
          cardID:cardID+1
        }),
      },
    }, 
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