<template>
  <div id="app">
        <header>
              傻狗
        </header>
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
