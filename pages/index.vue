<template>
  <section>
    <div v-bind-once="{ id: `div-1-${uid}` }">
      Lorem lispum 1
    </div>
    <div v-bind-once="{ id: `div-2-${uid}` }">
      Lorem lispum 2
    </div>
  </section>
</template>
<script setup>
  import { nanoid } from 'nanoid'
  const uid = nanoid()
</script>