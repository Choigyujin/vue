<template>
  <div id="app">
    <TodoHeader></TodoHeader>
    <TodoInput></TodoInput>
    <Todolist></Todolist>
    <TodoFooter></TodoFooter>
  </div>
</template>

<script>
import TodoHeader from './components/TodoHeader.vue'
import TodoInput from './components/Todoinput.vue'
import Todolist from './components/Todolist.vue'
import TodoFooter from './components/TodoFooter.vue'


export default {
  component:{
   'TodoHeader':TodoHeader,
   'TodoInput':TodoInput,
   'Todolist':Todolist,
   'TodoFooter':TodoFooter
  }
}
</script>

<style>

</style>