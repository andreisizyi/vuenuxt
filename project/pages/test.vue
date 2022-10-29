<template>
  <!-- <Tutorial/> -->
  <button @click="count++">{{ count }} this other page</button>
</template>

<script>
export default {
  name: 'TestPage',
  data: () => ({ count: 1 })
}
</script>
