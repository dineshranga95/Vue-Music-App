<template>
  <div class="form-group row ml-5">
      <label for="staticEmail" class="col-lg-2 control-label">Search music</label>
      <div class="col-lg-10">
        <input type="text"  class="form-control mr-5" id="staticEmail" placeholder="search here" @input="keypressed">
      </div>
    </div>
</template>

<script>
export default {
 methods:{
     keypressed(event){
         var key = event.target.value
         console.log(key);
     }
 }
}
</script>

<style>

</style>
