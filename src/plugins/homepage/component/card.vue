<template>
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
</template>

<style>
    ion-card{
        width: 40%;
        display: inline-block;
        height:270px;
        left:15px;
    };

    .imgs{
        display: inline-block;
    };

</style>
