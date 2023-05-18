<!-- Display today's date -->
<script lang="ts">
export default {
  data() {
    return {
      today: new Date().toLocaleDateString(),
    }
  },
}
</script>

<template>
  <div text-sm opacity-50>
    {{ today }}
  </div>
</template>
