<template>
  <h1>{{ message }}</h1>
  <HelloWorld />
</template>

<script>
 import HelloWorld from '~/components/Helloworld'

 export default {
     components: {
         HelloWorld
     },

     data() {
         return {
             message: 'hello Vue!!!'
         }
     }
 }
</script>
