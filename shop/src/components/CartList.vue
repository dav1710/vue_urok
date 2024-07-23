<script setup>
import Cart from './Cart.vue'
defineProps({
    items: Array    
})
const onClickAdd = () => {
  alert('add')
}
</script>

<template>
  <div class="grid grid-cols-4 gap-5">
    <Cart
    v-for="item in items"
      :key="item.id" 
      :title=item.title
      :price=item.price
      :imageUrl=item.imageUrl
      :isAdded="true"
      :isFavorite="true"
      :onClickAdd="onClickAdd"
    />
  </div>
</template>
