<template>
  <div class="min-h-screen bg-gray-50 flex flex-col items-center">
    <!-- Header Background -->
    <div class="w-full h-32 bg-gradient-to-r from-indigo-900 via-purple-800 to-indigo-700 relative">
      <div class="absolute inset-0 opacity-30 bg-[url('https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=800&q=80')] bg-cover bg-center"></div>
      <div class="absolute inset-0 bg-gradient-to-b from-black/40 to-transparent"></div>
      <!-- Logo -->
      <div class="relative z-10 flex items-center px-4 pt-4">
        <svg class="w-7 h-7 text-white" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <circle cx="12" cy="12" r="10" stroke="currentColor" stroke-width="2" fill="none"/>
          <path d="M8 12l2 2 4-4" stroke="currentColor" stroke-width="2" fill="none"/>
        </svg>
        <span class="ml-2 text-white font-semibold text-lg">fdhliakbar</span>
      </div>
    </div>

    <!-- Avatar -->
    <div class="-mt-14 z-10">
      <img src="/image/thiings-cat.png" alt="Avatar" class="w-24 h-24 rounded-full border-4 border-white shadow-lg object-cover"/>
    </div>

    <!-- Name & Description -->
    <div class="text-center mt-2 px-4">
      <h1 class="text-2xl font-bold">Muhamad Fadhli Akbar</h1>
      <p class="mt-2 text-gray-600 text-sm max-w-lg mx-auto break-words">
        <span class="inline-block align-middle mr-1">👋</span>
        Hi, call me Fadhli. I'm a Full Stack Developer with a passion for AI and Web3. Let’s build meaningful things together😺
      </p>
    </div>

    <!-- Social Icons -->
    <div class="flex justify-center space-x-4 mt-4">
      <a href="https://www.instagram.com/fdhliakbar/" class="text-gray-700 hover:text-pink-500"><i class="fab fa-instagram text-2xl"></i></a>
      <a href="https://x.com/Aozorasama1" class="text-gray-700 hover:text-black"><i class="fab fa-twitter text-2xl"></i></a>
      <a href="https://github.com/fdhliakbar" class="text-gray-700 hover:text-black"><i class="fab fa-github text-2xl"></i></a>
      <a href="https://www.hackerrank.com/profile/fadhliakbar125" class="text-gray-700 hover:text-green-600"><i class="fab fa-hackerrank text-2xl"></i></a>
      <a href="https://www.linkedin.com/in/muhamad-fadhli-akbar-a6961b307/" class="text-gray-700 hover:text-blue-600"><i class="fab fa-linkedin text-2xl"></i></a>
    </div>

    <!-- Main Link Button -->
    <div class="w-full max-w-md mt-6 px-4">
      <a href="https://github.com/fdhliakbar" target="_blank"
         class="flex items-center justify-between bg-black text-white rounded-xl py-3 px-5 font-semibold text-base shadow hover:bg-gray-800 transition">
        <span class="flex items-center">
          <i class="fas fa-globe mr-2"></i>
          Visit my website
        </span>
        <svg class="w-5 h-5 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
        </svg>
      </a>
    </div>

    <!-- Portfolio List -->
    <div class="w-full max-w-md mt-4 px-4 space-y-3">
      <!-- Link 1 -->
      <div class="flex items-center bg-white rounded-xl shadow px-4 py-3">
        <img src="/image/onodera-icon1.jpg" alt="Harmonica" class="w-12 h-12 rounded-lg object-cover mr-3"/>
        <div class="flex-1">
          <div class="font-semibold text-sm">Portfolio</div>
          <div class="text-xs text-gray-500">Coming Soon</div>
        </div>
        <span class="ml-2 bg-purple-100 text-purple-700 font-bold text-xs px-3 py-1 rounded-lg">Nanti di Update</span>
      </div>
      <!-- Link 2 -->
      <div class="flex items-center bg-white rounded-xl shadow px-4 py-3">
        <a href="https://github.com/fdhliakbar" target="_blank" class="flex items-center w-full">
        <div class="w-12 h-12 rounded-lg bg-gradient-to-br from-black to-indigo-600 flex items-center justify-center mr-3">
          <i class="fab fa-github text-white text-2xl"></i>
        </div>
        <div class="flex-1">
          <div class="font-semibold text-sm">Visit my Github</div>
        </div>
        <svg class="w-5 h-5 text-gray-400 ml-2" fill="none" viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-width="2" d="M17 8l4 4m0 0l-4 4m4-4H3"/>
        </svg>
      </a>
      </div>
      <!-- Link 3 -->
      <div class="flex items-center bg-white rounded-xl shadow px-4 py-3">
        <img src="/image/onodera-icon1.jpg" alt="E-Book" class="w-12 h-12 rounded-lg object-cover mr-3"/>
        <div class="flex-1">
          <div class="font-semibold text-sm">Portfolio</div>
        </div>
        <span class="ml-2 bg-purple-100 text-purple-700 font-bold text-xs px-3 py-1 rounded-lg">Nanti di Update</span>
      </div>
    </div>

    <!-- Footer -->
    <footer class="mt-auto py-6 text-center text-xs text-gray-400">
      © 2025 Muhamad Fadhli Akbar. All rights reserved.
    </footer>
  </div>
</template>

<script setup lang="ts">
// ...existing code...
</script>

<!-- Tambahkan CDN fontawesome di index.html untuk ikon sosial -->
<style>
/* ...existing code... */
</style>