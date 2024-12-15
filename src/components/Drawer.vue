<script setup>
import DrawerHead from './DrawerHead.vue'
import CartListItem from './CartListItem.vue'
</script>

<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed right-0 top-0 z-20 p-8">
    <DrawerHead />

    <CartListItem />

    <div class="flex flex-col gap-3 mt-5">
      <div class="flex gap-2">
        <span>Total:</span>
        <div class="flex-1"></div>
        <b>600 zł</b>
      </div>

      <div class="flex gap-2">
        <span>Develivery:</span>
        <div class="flex-1"></div>
        <b>25 zł</b>
      </div>
      <button
        disabled
        class="bg-black text-white w-full rounded-2xl py-3 mt-5 disabled:bg-zinc-400 hover:bg-zinc-900 transition hover:scale-105 active:bg-zinc-800 cursor-not-allowed"
      >
        Checkout
      </button>
    </div>
  </div>
</template>
