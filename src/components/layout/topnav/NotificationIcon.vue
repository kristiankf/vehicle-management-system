<template>
  <div class="hover:bg-blue-100 p-1 size-10 flex justify-center items-center rounded-full relative">
    <Icon icon="heroicons:bell" class="text-2xl" />

    <!-- badge -->
    <div class="absolute bg-red-500 text-white text-[12px] py- px-1.5 rounded-full -top-1 right-0">
      3
    </div>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'
</script>

<style lang="scss" scoped></style>
