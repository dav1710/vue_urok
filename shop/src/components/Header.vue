<template>
    <header class="flex justify-between border-b border-slate-200 px-10 py-8">
      <div class="flex items-center gap-4">
        <img src="/logo.png" alt="Logo" class="w-10" />
        <div>
          <h2 class="text-xl font-bold uppercase">Vue Sneakers</h2>
          <p class="text-slate-400">The best sneaker store</p>
        </div>
      </div>

      <ul class="flex items-center gap-10">
        <li class="flex items-center gap-3 cursor-pointer text-gray-500 hover:text-black">
          <img src="/cart.svg" alt="Cart">
          <b>1000 USD</b>
        </li>
        <li class="flex items-center gap-3 cursor-pointer text-gray-500 hover:text-black">
          <img src="/heart.svg" alt="heart">
          <span>Favorite</span>
        </li>
        <li class="flex items-center gap-3 cursor-pointer text-gray-500 hover:text-black">
          <img src="/profile.svg" alt="heart">
          <span>Profile</span>
        </li>
      </ul>
    </header>
</template>