<template>
  <div>Error: {{ error.response.data }}</div>
</template>

<script>
export default {
  // eslint-disable-next-line vue/require-prop-types
  props: ['error']
}
</script>
