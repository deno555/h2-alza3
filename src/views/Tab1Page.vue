<template>
    <Homepage/>
</template>

<script>
  import { defineComponent } from 'vue';
  import Homepage from '@/plugins/homepage/view/homepage.vue';

  export default  defineComponent({
    name: 'Tab1Page',
    components:{
      Homepage
    },})
</script>