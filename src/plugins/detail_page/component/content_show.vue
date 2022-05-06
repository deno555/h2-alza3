<template>
  
</template>

<script>
import axios from 'axios';
export default {
    data(){
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
