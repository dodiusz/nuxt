<template>
  <div>
    <TheHeader />
    <nuxt />
    <TheFooter />
  </div>
</template>

<script>
import TheHeader from '~/components/MyHeader'
import TheFooter from '~/components/MyFooter'
export default {
  components: {
    TheHeader,
    TheFooter
  }
}
</script>
