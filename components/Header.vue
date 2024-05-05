<template>
  <header class="bg-slate-900 py-2">
    <main class="container mx-auto flex flex-row justify-between">
      <div class="text-white text-lg font-bold"> 
         <nuxt-link to="/">Site Name</nuxt-link>
      </div>
      <nav class="flex flex-row justify-end gap-4">
      <nuxt-link to="/pricing">Page 1</nuxt-link>
      <nuxt-link to="/protfolio">Page 2</nuxt-link>
      <nuxt-link to="/about">Page 3</nuxt-link>
      <nuxt-link to="/page4">Page 4</nuxt-link>
      </nav>
    </main>
  </header>
</template>