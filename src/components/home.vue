<template>
  <div class="container" >
  
   <form class="form-horizontal ml-5 mr-5">
  <fieldset>
    <legend>Music app</legend>
    <app-search></app-search>
   
 </fieldset>  
</form>
    <div class="row mt-2" >
     <app-result></app-result>
      
    </div>
  </div>
</template>

<script>
import searcharea from './searchArea.vue'
import resultarea from './resultArea.vue'
export default {
components:{
  'app-search':searcharea,
  'app-result':resultarea
}
}
</script>
 
<style>

</style>
