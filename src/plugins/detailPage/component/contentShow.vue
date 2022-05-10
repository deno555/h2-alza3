<template>
    <ion-page>
        <ion-content>
            <div>
                <h5>Name: {{props.content.Fullname}}</h5>
                <ion-item-divider/>
                <h5>Proffesion: {{props.content.Proffesion}}</h5>
                <ion-item-divider/>
                <h5>Proffesion Language: {{props.content.Proffesion_Language}}</h5>
                <ion-item-divider/>
                <h5>Proffesion Language Level: {{props.content.Proffesion_Language_Level}}</h5>
                <ion-item-divider/>
                <h5>Language: {{props.content.Language}}</h5>
                <ion-item-divider/>
                <h5>Language Level: {{props.content.Language_Level}}</h5>
                <ion-item-divider/>
                <h5>Pay: {{props.content.Pay}}</h5>
                <ion-item-divider/>
                <h5>Contact Info:</h5>
                <ion-item-divider/>
                <h5>Email: {{props.content.Contact_Info.Email}}</h5>
                <ion-item-divider/>
                <h5>Telephoe: {{props.content.Contact_Info.Telehone}}</h5>
                <ion-item-divider/>
                <h5>City:{{props.content.City}}</h5>
                <ion-item-divider/>
                <h5>Description: {{props.content.Description}}</h5>
                <ion-item-devider/>
            </div>
        </ion-content>
    </ion-page>
</template>
<script>
import axios from 'axios';
import {IonItemDivider, IonPage, IonContent} from '@ionic/vue';


export default {
    components: {IonItemDivider, IonPage, IonContent},
    data(){``
        return{
            props: {content : [{
                Fullname: [{Name: '', Surname: ''}], Proffesion: '', Proffesion_Language: ['', '', ''], Proffesion_Language_Level: ['', '', ''], Language: '', Language_Level: [''], Pay: '', Contact_Info: [{Email: '', Telephone: ''}], City: '', Description: ''
              }]},

         }
    },

    methods:{
        getList(){
            axios.get('http://127.0.0.1:8000/api/v1/mods/').then((response) => {
            response.data;
            }
        )},
    }
}


</script>
