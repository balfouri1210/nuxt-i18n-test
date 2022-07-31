<template>
<div>
  <nuxt-link :to="localePath({
    name: 'brandName-brandId',
    params: {
      brandName: 'apple',
      brandId: 1
    }
  })" :style="{
    fontSize: '28px'
  }">브랜드페이지로</nuxt-link>
  <Tutorial/>
</div>
</template>

<script>
export default {
  name: 'IndexPage'
}
</script>
