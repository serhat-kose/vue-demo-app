<template>
<div class="holder">
 <ul>
   <li v-for="(data,index) in lessons" :key='index'>
     {{index}}.{{data.lesson}}
   </li>
 </ul>

</div>
</template>

<script>
export default {
  name: 'Demo',
 data(){
   return{
     lessons:[
       {"lesson":"Math"},
       {"lesson":"Eng"}
     ]
   }
 }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>


</style>
