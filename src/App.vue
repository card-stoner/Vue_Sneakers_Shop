<script setup>
import Header from './components/Header.vue'
import CartList from './components/CartList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <Drawer />
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-2xl mt-14">
    <Header />

    <div class="p-8">
      <h1 class="text-3xl font-bold">Все кроссовки</h1>
    </div>

    <CartList />
  </div>
</template>
