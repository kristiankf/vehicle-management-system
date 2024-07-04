<template>
  <div>
    <div class="primary-bg rounded-md p-2 max-w-[250px] flex items-center gap-2">
      <Icon icon="material-symbols:search-rounded" class="text-xl text-gray-500" />
      <input
        class="w-full primary-bg text-sm focus:outline-none"
        placeholder="Search..."
        type="text"
      />
    </div>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'
</script>

<style lang="scss" scoped></style>
