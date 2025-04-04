<template>
  <div class="flex flex-col items-center text-gray-600">
    <div class="bg-gray-100 p-3 rounded-full">
      <Icon :name="icon" class="w-6 h-6 text-blue-600" />
    </div>
    <span class="text-xs mt-1 text-center">{{ text }}</span>
  </div>
</template>

<script setup>
defineProps(["icon", "text"]);
</script>
