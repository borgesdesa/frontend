<template>
  <v-footer height="60" class="d-block text-center">
    <p>2021. CCT Guided Project Bruno Borges de Sa</p>
  </v-footer>
</template>

<script>
export default {
  name: 'Footer',
  computed: {
    appVersion() {
      return this.$store.getters.appVersion
    }
  }
}
</script>
