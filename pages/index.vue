<template>
<div>
  <nuxt-link :to="localePath({
    name: 'brandName-brandId',
    params: {
      brandName: 'apple-&',
      brandId: 1
    }
  })" :style="{
    fontSize: '28px'
  }">Click here for testing nuxt-i18n issue</nuxt-link>
  <!-- <Tutorial/> -->
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
