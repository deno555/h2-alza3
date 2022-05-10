<template>
  <HomePage/>
</template>

<script>
  import { defineComponent } from 'vue';
  import HomePage from "@/plugins/homepage/view/HomePage.vue"

  export default  defineComponent({
    name: 'Tab1Page',
    components:{
      HomePage
    },})
</script>