<template>
  <div class="bg-[#0c0822] text-white h-full p-4">
    <!-- logo -->
    <div class="">
      <h1 class="text-cyan-500 font-bold text-4xl text-center my-4">FLEET</h1>
    </div>

    <!-- title -->
    <div class="my-7">
      <h3 class="uppercase text-xs gray-text font-bold">Menu</h3>
    </div>

    <div>
      <ul>
        <template v-for="item in links" :key="item.name">
          <router-link :to="{}">
            <li
              class="gray-text mb-6 flex justify-between items-center hover:text-[#eee] cursor-pointer transition"
            >
              <span>{{ item.name }}</span
              ><Icon icon="heroicons:chevron-right-16-solid" />
            </li>
          </router-link>
        </template>
      </ul>
    </div>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'
const links = [
  { name: 'Staff Management', link: '#' },
  { name: 'Vehicle Management', link: '#' },
  { name: 'Supplier Management', link: '#' }
]
</script>

<style scoped></style>
