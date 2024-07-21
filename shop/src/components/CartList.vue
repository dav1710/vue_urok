<script setup>
import Cart from './Cart.vue'

const onClickAdd = () => {
    alert('add')
}
</script>

<template>
    <div class="grid grid-cols-4 gap-5">
        <Cart 
            title="Men Sneakers Nike Blazer Mid Suede" 
            :price="1000" 
            imageUrl="/sneakers/sneakers-1.jpg" 
            :isAdded="true"
            :isFavorite="true"
            :onClickAdd="onClickAdd"
            />
      </div>
</template>