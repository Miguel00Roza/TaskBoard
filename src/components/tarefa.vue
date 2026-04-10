<script setup>
const props = defineProps({
  descricao: String,
  status: String
})
</script>
<template>
<div :class="props.status">
  {{ props.desc }}
</div>
</template>
<style scoped>

</style>
