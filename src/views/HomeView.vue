<script setup lang="ts">
import Todos from "../Components/Todos.vue";
component: {
  Todos;
}
</script>

<template>
  <main class="App-container">
    <h1>Todo App</h1>
    <div class="content-container">
      <Todos />
    </div>
  </main>
</template>
