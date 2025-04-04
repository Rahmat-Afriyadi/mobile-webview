<template>
  <nav class="fixed bottom-0 left-0 w-full bg-white shadow-lg border-t flex justify-around items-center px-3 py-1">
    <NuxtLink to="/" class="flex flex-col items-center text-gray-600 hover:text-blue-500">
      <Icon name="lucide:home" class="w-6 h-6" />
      <span class="text-xs">Beranda</span>
    </NuxtLink>

    <NuxtLink to="/aktivitas" class="flex flex-col items-center text-gray-600 hover:text-blue-500">
      <Icon name="lucide:list" class="w-6 h-6" />
      <span class="text-xs">Aktivitas</span>
    </NuxtLink>

    <!-- Center button -->
    <div class="relative">
      <button
        class="bg-green-500 text-white rounded-full w-12 h-12 flex justify-center items-center shadow-lg -translate-y-4"
      >
        <Icon name="lucide:camera" class="w-6 h-6" />
      </button>
    </div>

    <NuxtLink to="/notifikasi" class="flex flex-col items-center text-gray-600 hover:text-blue-500">
      <Icon name="lucide:bell" class="w-6 h-6" />
      <span class="text-xs">Notifikasi</span>
    </NuxtLink>

    <NuxtLink to="/profil" class="flex flex-col items-center text-gray-600 hover:text-blue-500">
      <Icon name="lucide:user" class="w-6 h-6" />
      <span class="text-xs">Profil</span>
    </NuxtLink>
  </nav>
</template>
