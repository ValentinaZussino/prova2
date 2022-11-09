<!-- tamplate -->
<template>
    <HeaderComponentVue/>
    <p>{{message}}</p>
  
</template>

<!-- script -->
<script>
import HeaderComponentVue from './components/HeaderComponent.vue';
export default{
  components: {
    HeaderComponentVue,
  },
  data(){
    return {
      message: 'Hello!'
    }
  }, 
  methods: {

  }
}
</script>

<!-- style -->
<style lang="css">
p {
  color: rgb(184, 23, 23);
}
</style>
