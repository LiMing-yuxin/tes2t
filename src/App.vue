<template>
  <div id="app">
          <h1>在master分支</h1>
          <h2>1</h2>
    <router-view/>
  </div>
</template> 

<script>
export default {
  name: 'App'
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
  header{
    width: 100%;
    height: 50px;
    background: red;
    color: white;
    line-height: 50px;
    text-align: center;
  }
</style>
