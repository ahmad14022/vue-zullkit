<template>
  <div
    class="items-center justify-between hidden w-full md:flex md:w-auto md:order-1"
    id="mobile-menu-2"
  >
    <ul
      class="flex flex-col mt-4 md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-regular"
    >
      <li>
        <router-link
          to="/"
          class="block py-2 pl-3 pr-4 text-white bg-indigo-600 rounded md:bg-transparent md:text-indigo-600 md:p-0 dark:text-white"
          aria-current="page"
         >Home</router-link>
        
      </li>
      <li>
        <router-link
          to="/categories"
          class="block py-2 pl-3 pr-4 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-indigo-600 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
          >Categories</router-link>
        
      </li>
      <li>
        <router-link
          to="/pricing"
          class="block py-2 pl-3 pr-4 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-indigo-600 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
          >Pricing</router-link>
        
      </li>
      <li>
        <router-link
          to="/"
          class="block py-2 pl-3 pr-4 text-gray-700 border-b border-gray-100 hover:bg-gray-50 md:hover:bg-transparent md:border-0 md:hover:text-indigo-600 md:p-0 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700"
          >Study Case</router-link>
        
      </li>
    </ul>
  </div>
</template>

<script setup>
import {RouterLink} from 'vue-router'
</script>

<style></style>
