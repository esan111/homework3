<script setup>
  import {ref} from "vue"

  const name = ref('')

</script>

<template>

<main class="app">

  <secion class="greeting">
    <h2 class="title">
      Welcome back, <input type="text" placeholder="Enter Name" v-model="name"
    </h2>
  </secion>

  <section class="create-todo">


  </section>

  <section class="todo-list">

  </section>

</main>

</template>
