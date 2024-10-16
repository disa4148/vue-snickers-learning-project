<script setup>
import Card from './Card.vue'
defineProps({
  items: Array,
})
</script>

<template>
  <div class="grid grid-cols-4 gap-5 p-4">
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Air Blazer Mid Suede"
      :price="1500"
      :is-added="true"
      :is-favorite="true"
    />
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Air Blazer Mid Suede"
      :price="1500"
      :is-added="false"
      :is-favorite="false"
    />
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Air Blazer Mid Suede"
      :price="1500"
      :is-added="true"
      :is-favorite="false"
    />
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Air Blazer Mid Suede"
      :price="1500"
      :is-added="false"
      :is-favorite="true"
    />
    <Card
      image-url="/sneakers/sneakers-1.jpg"
      title="Мужские кроссовки Nike Air Blazer Mid Suede"
      :price="1500"
      :is-added="true"
      :is-favorite="true"
    />
  </div>
</template>
