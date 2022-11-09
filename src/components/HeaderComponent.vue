<template>
  <header>
    <h1>{{title}}</h1>
  </header>
</template>
<!-- script -->
<script>
export default{
    name: 'HeaderComponent',
    data(){
        return {
        title: 'Hi!'
        }
    }, 
}
</script>

<!-- style -->
<style lang="css">
header {
    width: 100%;
    height: 50px;
    background-color: black;
}
h1 {
  color: violet;
}
</style>