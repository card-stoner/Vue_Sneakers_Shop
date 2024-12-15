<script setup>
defineProps({
  title: String,
  imageUrl: String,
  price: Number,
  isFavorite: Boolean,
  isAdedd: Boolean,
  onClickAdd: Function,
  onClickFavorite: Function,
})

const onClickAdd = () => {
  alert(111)
}
</script>

<template>
  <div>
    <div
      class="relative bg-white border border-gray-300 rounded-3xl p-8 cursor-pointer transition hover:-translate-y-2 hover:shadow-2xl"
    >
      <img
        :src="!isFavorite ? '/like-2.svg' : '/like-1.svg'"
        alt="like 1"
        class="absolute top-8 left-8"
        @click="onClickAdd"
      />

      <img :src="imageUrl" alt="Sneaker" />

      <p class="mt-2">{{ title }}</p>

      <div class="flex justify-between mt-5">
        <div class="flex flex-col">
          <span class="text-slate-400">Цена: </span>
          <b>{{ price }} zł</b>
        </div>

        <img @click="onClickAdd" :src="!isAdedd ? '/plus.svg' : '/checked.svg'" alt="plus" />
      </div>
    </div>
  </div>
</template>
