<!-- tamplate -->
<template>
    <HeaderComponent/>
    <p>{{message}}</p>
    <FooterComponent/>
</template>

<!-- script -->
<script>
import HeaderComponent from './components/HeaderComponent.vue';
import FooterComponent from './components/FooterComponent.vue';
export default{
  components: {
    HeaderComponent,
    FooterComponent,
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
