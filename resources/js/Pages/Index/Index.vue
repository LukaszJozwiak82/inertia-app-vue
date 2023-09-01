<script setup>
  import {Link} from '@inertiajs/vue3'
  defineProps({
    message: String
  })

</script>

<template>
<div>Index</div>
  <Link href="/hello">Show Page</Link>
  To jest: {{ message }}
</template>

<style scoped>

</style>