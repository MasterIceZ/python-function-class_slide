<template>
  <footer
    v-if="$slidev.nav.currentPage !== 1 && $slidev.nav.currentPage !== $slidev.nav.total + 1"
    class="absolute bottom-1 right-3"
  >
  Page {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
  </footer>
</template>
