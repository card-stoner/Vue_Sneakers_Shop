<script setup>
import Cart from './Cart.vue'

const onClickAdd = () => {
  alert(111)
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5 px-8">
    <Cart
      title="Nike Blazer Mid"
      image-url="/sneakers/sneakers-1.jpg"
      :price="400"
      is-favorite="false"
      :onClickAdd="onClickAdd"
      :is-adedd="true"
    />
  </div>
</template>
