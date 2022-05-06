<template>
    <header_2 />
    <div>
        <a><img src = "" /></a>
    </div>
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
        <h5>City: {{props.content.City}}</h5>
        <ion-item-divider/>
        <h5>Description: {{props.content.Description}}</h5>
        <ion-item-divider/>
    </div>
</template>

<script>
import header_2 from '@/src/plugins/global_component/header_2.vue';
import content_show from '@/plugins/detail_page/component/content_show.vue'

export default {
    components: [{header_2, content_show}]
}
</script>