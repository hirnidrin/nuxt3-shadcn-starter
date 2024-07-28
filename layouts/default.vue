<template>
  <div class="container mx-auto bg-gray-200 max-w-screen-xl">
    <div class="min-h-screen flex flex-col">
      <!-- Header -->
      <header class="bg-gray-300 py-4 flex justify-between items-center">
        <img src="/logo.png" alt="Logo">
        <h1 class="text-4xl font-bold">My smart site title</h1>
      </header>
      <!-- Main Content -->
      <main class="container mx-auto bg-gray-100 flex-grow px-0 py-4">
        <slot />
      </main>
      <!-- Footer -->
      <footer class="bg-gray-300 py-4 text-center">
        <p>Your Footer Text</p>
      </footer>
    </div>
  </div>
</template>
