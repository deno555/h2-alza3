<template>
    <div v-for="(i) in card" :key="i.cardTitle">
      <ion-card>
        <ion-card-header>
        <div class="images">
          <img class="img1" src="https://www.business2community.com/wp-content/uploads/2017/08/blank-profile-picture-973460_640.png">
          <img width="40" class="img2" src="https://images.emojiterra.com/google/noto-emoji/v2.034/share/1f3c5.jpg">
        </div>
        </ion-card-header>

        <ion-card-content>
          <p>Meno</p>
          <p>Mesto</p>
          <p>Jaziky</p>
          <p>Plat</p>
          <p>Skusenosti</p>
        </ion-card-content>
      </ion-card>
  </div>
</template>



<script>
    export default{
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
            }
        },
            methods:{
                addCard(cardID){
                    this.card.push({
                    cardID:cardID+1,
                    })
            },
        },
    }
    
</script>

<style>
    .images{
        
    }

    ion-card{
        display: grid;
        width: 38%;
        display: inline-block;
        height:270px;
        left:15px;
        top: 0px;
    };

    .img1{
        width: 100px;
     };

    .img2{
        position: absolute;
        width: 4px;
    };

</style>