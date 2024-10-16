<script setup>
import CartItem from './CartItem.vue'
import CartItemList from './CartItemList.vue'
import DrawerHead from './DrawerHead.vue'
import DrawerFooter from './DrawerFooter.vue'
</script>

<template>
  <div class="fixed z-10 top-0 h-full w-full bg-black opacity-70" />
  <div
    class="flex flex-col justify-between fixed z-10 top-0 h-full right-0 w-96 bg-white px-10 py-7"
  >
    <DrawerHead />
    <div class="flex flex-col flex-1 justify-between">
      <CartItemList />
      <DrawerFooter />
    </div>
  </div>
</template>
