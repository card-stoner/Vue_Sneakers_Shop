<template>
  <header class="flex justify-between border-b border-gray-300 px-8 p-2">
    <div class="flex items-center gap-4">
      <img src="/logo.png" alt="logo" class="w-10" />
      <div>
        <h2 class="text-xl font-bold uppercase">rexa6 Shop</h2>
        <p class="text-slate-400">The best sneakers in the world</p>
      </div>
    </div>

    <ul class="flex items-center gap-10">
      <li class="flex items-center cursor-pointer gap-2 text-zinc-500 hover:text-black">
        <img src="/cart.svg" alt="Cart" />
        <span>400 zl.</span>
      </li>
    </ul>

    <ul class="flex items-center">
      <li class="flex items-center cursor-pointer gap-2 text-zinc-500 hover:text-black">
        <img src="/heart.svg" alt="Cart" />
        <span>Закладки</span>
      </li>
    </ul>

    <ul class="flex items-center">
      <li class="flex items-center cursor-pointer gap-2 text-zinc-500 hover:text-black">
        <img src="/profile.svg" alt="Cart" />
        <span>Profile</span>
      </li>
    </ul>
  </header>
</template>
