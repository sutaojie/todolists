<template>
  <div id="app" class="app">
  <to-aside/>
  <todo-lists/>
  </div>
</template>

<script>
import './vendor/reset.css'
import ToAside from './components/ToAside'
import TodoLists from './components/TodoLists'
export default {
  name: 'App',
  components:{
    ToAside,
    TodoLists
  }
}
</script>

<style>
.app{
  display: flex
}
</style>
