<template>
  <div class="bg-zinc-900 absolute top-1/2 left-1/2 transform -translate-x-1/2 -translate-y-1/2">
    <input type="file" id="file-chooser" class="bg-blue-500 hover:bg-blue-700 text-black font-bold py-2 px-4 rounded"/>
    <br>
        <button id="upload-button" class="mt-5">Upload to S3</button>
        <div id="results"></div>
  </div>
</template>

<script>
    import axios from 'axios'
    const url = 'http://localhost:5005/'
export default {
  data () {
    return {
      
      
      
    }
  }
}
</script>

<style>

</style>