<template>
  <div id="app">
    <div id="parent" class="bg-success">
      <div class="bg-light text-success text-center shadow rounded text-monospace">
        单词本
      </div>
      <p>
        English Word Book
      </p>
    </div>
  </div>
</template>

<script>
import 'bootstrap/dist/css/bootstrap.min.css'
import 'bootstrap/dist/js/bootstrap.min.js'
export default {
  name: 'App',
}
</script>

<style>
#parent{
  height: 503px;
  position: relative;
}
#parent div{
  height: 127px;
  width: 210px;
  line-height: 127px;
  font-size: 2.5rem;
  position: absolute;
  top:162px;
  left: 222px;

}
</style>
