<template>
  <!-- <Tutorial/> -->
  <button @click="count++">{{ count }}</button>
</template>

<script>
export default {
  name: 'IndexPage',
  data: () => ({ count: 1 })
}
</script>
