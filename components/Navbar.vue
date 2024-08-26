<template>
     <nav class="bg-red-600 fixed top-0 left-0 w-full z-50">
    <div class="container mx-auto px-4 py-4 flex items-center justify-between">
      <!-- Left side with the logo and menu items -->
      <div class="flex items-center space-x-4">
        <!-- Logo -->
        <div class="text-white font-bold text-2xl">SKÆBNER</div>

        <!-- Menu Items -->
        <div class="hidden lg:flex space-x-4">
          <a href="#" class="text-white uppercase font-bold">Livsstil</a>
          <a href="#" class="text-white uppercase font-bold">Sund</a>
          <a href="#" class="text-white uppercase font-bold">Krimi</a>
          <a href="#" class="text-white uppercase font-bold">Spirituelt</a>
          <a href="#" class="text-white uppercase font-bold">Horoskop</a>
        </div>
      </div>

      <!-- Right side with the buttons -->
      <div class="flex items-center space-x-4">
        <button class="bg-yellow-500 text-black font-bold py-1 px-3 rounded">Abonnér</button>
        <button class="text-white">
          <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"/>
          </svg>
        </button>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Navbar',
}
</script>