<script setup>
import DrawerHead from './DrawerHead.vue'
import CartListItem from './CartListItem.vue'
</script>
<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed top-0 right-0 z-20 p-8">
    <DrawerHead />
    <CartListItem />

    <div class="flex flex-col gap-4 mt-7">
      <div class="flex gap-2">
        <span>Total</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>12000 USD</b>
      </div>

      <div class="flex gap-2">
        <span>Tax 5%</span>
        <div class="flex-1 border-b border-dashed"></div>
        <b>600 USD</b>
      </div>

      <button
        disabled
        class="mt-4 transition bg-lime-500 w-full rounded-xl py-3 disabled:bg-slate-400 text-white font-bold hover:bg-lime-600 active:bg-lime-700"
      >
        Check Order
      </button>
    </div>
  </div>
</template>
