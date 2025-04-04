<template>
  <div class="pb-16 bg-white">
    <!-- Header Section -->
    <header class="bg-blue-900 text-white text-center aspect-video">
      <img src="/images/hero.jpeg" alt="" class="w-full h-full object-cover" />
    </header>

    <!-- Search Bar -->
    <div class="p-4 relative -translate-y-9">
      <div class="bg-gray-100 rounded-full px-3 py-2 shadow-md flex items-center">
        <Icon name="lucide:search" class="text-gray-500 w-5 h-5 mx-2" />
        <input
          type="text"
          placeholder="Cari Layanan di JAKI?"
          class="bg-transparent outline-none flex-1 text-slate-900"
        />
      </div>
    </div>

    <!-- Quick Action Buttons -->
    <div class="grid grid-cols-4 gap-4 p-4 -mt-11">
      <ActionButton icon="lucide:megaphone" text="Laporan Warga" />
      <ActionButton icon="lucide:newspaper" text="Berita" />
      <ActionButton icon="lucide:receipt" text="Pajak" />
      <ActionButton icon="lucide:shopping-bag" text="Harga Pangan" />
      <ActionButton icon="lucide:bus" text="Transportasi Publik" />
      <ActionButton icon="lucide:cloud" text="Kualitas Udara" />
      <ActionButton icon="lucide:ambulance" text="Ambulans" />
      <ActionButton icon="lucide:more-horizontal" text="Semua" />
    </div>

    <!-- JakOne Pay -->
    <div class="bg-white shadow-md rounded-xl p-4 mx-4 flex justify-between items-center">
      <div>
        <h2 class="text-gray-600 text-sm">JakOne Pay</h2>
        <p class="text-gray-400 text-xs">Belum aktif</p>
      </div>
      <NuxtLink to="#" class="text-blue-500 text-xs bg-blue-200 px-3 py-1 rounded-lg font-bold">Hubungkan</NuxtLink>
    </div>

    <!-- Banner -->
    <div class="p-4">
      <div class="bg-blue-500 text-white p-6 rounded-xl shadow-lg">
        <h2 class="text-lg font-semibold">Menuju 500 Tahun Jakarta</h2>
        <p class="text-sm">Yuk, ramein di sini!</p>
      </div>
    </div>

    <!-- Recommended Features -->
    <div class="p-4">
      <h2 class="text-center text-black font-semibold">Cari Fitur yang Paling Pas Buat Kamu</h2>
    </div>

    <!-- Bottom Navigation Bar -->
    <BottomNavbar />
  </div>
</template>

<script setup>
import BottomNavbar from "~/components/BottomNavbar.vue";
import ActionButton from "~/components/ActionButton.vue";
</script>
