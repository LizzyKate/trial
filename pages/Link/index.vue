<template>
  <div>
    <Link />
  </div>
</template>
<script>
import Link from '~/components/Link/link'
export default {
  components: {
    Link,
  },
  transition(to, from) {
    if (to) {
      return 'slide-fade'
    }
  },
}
</script>
<style scoped></style>
