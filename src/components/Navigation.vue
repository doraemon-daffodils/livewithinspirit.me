<script setup lang="ts">
import { isDark, toggleDark } from '~/logic'

</script>

<template>
  <nav
    z="100"
    text="dark-100 dark:light-900"
    position="fixed top-0 left-0 right-0"
    bg="dark:(dark-500 opacity-50) white opacity-75"
    backdrop="~ blur-lg"
    h="18"
    p="x-4"
    border="b-1 dark:dark-500"
  >
    <div
      max-w="screen-lg"
      m="x-auto"
      h="full"
      flex="~ row"
      items="center"
      space="x-4"
    >
      <router-link to="/" flex="1">
        <Logo />
      </router-link>
       
    <router-link to="/">
        Home
      </router-link>
      <router-link to="/inspiration">
        My Inspirations
      </router-link>

      <router-link to="/notes">
        My Notes
      </router-link>

      <a href="https://twitter.com" target="_blank" rel="noreferrer noopener">
        <mdi-twitter />
      </a>
      
      <a cursor="pointer" @click="toggleDark">
        <carbon-moon v-if="isDark" />
        <carbon-sun v-else />
      </a>
    </div>
  </nav>
</template>
