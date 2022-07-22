<template>
  <footer
    v-if="$slidev.nav.currentLayout !== 'cover'"
    class="absolute bottom-1 right-3"
  >
  Page {{ $slidev.nav.currentPage }} of {{ $slidev.nav.total }}
  </footer>
</template>
