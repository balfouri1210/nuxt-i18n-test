<template>
  <div>
    <h1>{{ this.$t('welcome') }}</h1>

    <h2>brandName: {{ this.$route.params.brandName }}</h2>
    <h2>brandId: {{ this.$route.params.brandId }}</h2>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>