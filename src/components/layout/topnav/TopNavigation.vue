<template>
  <div class="bg-white maximum-width border-b sticky top-0">
    <nav class="flex gap-5">
      <div class="py-4 flex justify-between items-center w-full">
        <!-- search and collapse icon -->
        <div class="flex items-center gap-4">
          <Icon icon="heroicons:bars-3-bottom-left" class="gray-text text-3xl" />
          <SearchBar />
        </div>

        <!-- Icons -->
        <div class="flex gap-2">
          <ThemeIcon />
          <NotificationIcon />
        </div>
      </div>

      <!-- user profile -->
      <div class="w-fit shrink-0">
        <UserProfile />
      </div>
    </nav>
  </div>
</template>

<script setup>
import { Icon } from '@iconify/vue'
import SearchBar from '@/components/ui/SearchBar.vue'
import NotificationIcon from '@/components/layout/topnav/NotificationIcon.vue'
import ThemeIcon from '@/components/layout/topnav/ThemeIcon.vue'
import UserProfile from '@/components/layout/topnav/UserProfile.vue'
</script>

<style lang="scss" scoped></style>
