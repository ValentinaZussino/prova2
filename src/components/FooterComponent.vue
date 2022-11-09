<template>
    <footer>
      <span>{{span}}</span>
    </footer>
  </template>
  <!-- script -->
  <script>
  export default{
      name: 'FooterComponent',
      data(){
          return {
          span: 'ciao ciao!'
          }
      }, 
  }
  </script>
  
  <!-- style -->
  <style lang="css">
  footer {
      width: 100%;
      height: 50px;
      background-color: black;
  }
  span {
    color: rgb(213, 250, 30);
  }
  </style>