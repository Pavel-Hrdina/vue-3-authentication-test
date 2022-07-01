<template>
  <nav class="border-gray-200 h-10 rounded flex flex-row p-4 mx-auto w-1/2">
    <div class="flex-1">
      <router-link to="/"
        ><h2 class="font-extrabold text-xl">Authentication Test</h2>
      </router-link>
    </div>
    <div class="flex-none w-auto">
      <router-link to="/login" class="px-3 font-semibold text-blue-300"
        >Sign in</router-link
      >
      <router-link to="/" class="px-3 font-semibold text-blue-300"
        >Register</router-link
      >
    </div>
  </nav>
</template>
