<template>
  <div class="home">
    <AddTodo />
    <FilterTodos />
    <Todos />
  </div>
</template>

<script>
// @ is an alias to /src
import Todos from '@/components/Todos'
import AddTodo from '@/components/AddTodo'
import FilterTodos from '@/components/FilterTodos'

export default {
  name: 'Home',
  components: {
    Todos,
    AddTodo,
    FilterTodos
  }
}
</script>
