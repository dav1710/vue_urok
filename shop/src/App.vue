<script setup>
import Header from './components/Header.vue'
import CartList from './components/CartList.vue'
import Drawer from './components/Drawer.vue'
</script>

<template>
  <!-- <Drawer /> -->
  <div class="bg-white w-4/5 m-auto rounded-xl shadow-xl mt-14">
    <Header />

    <div class="p-10">
      <div class="flex justify-between items-center mb-8">
        <h2 class="text-3xl font-bold">All Sneakers</h2>
        <div class="flex gap-4">
          <select class="py-2 px-3 border rounded-md outline-none" name="" id="">
            <option value="Name">Name</option>
            <option value="Price (Hight)">Price (Hight)</option>
            <option value="Price (Low)">Price (Low)</option>
          </select>
          <div class="relative">
            <img class="absolute left-3 top-3" src="/search.svg" alt="search" />
            <input
              class="border rounded-md py-2 pl-12 pr-4 outline-none focus:border-gray-400"
              type="text"
              placeholder="Search..."
            />
          </div>
        </div>
      </div>
      <CartList />
    </div>
  </div>
</template>

<style scoped></style>
