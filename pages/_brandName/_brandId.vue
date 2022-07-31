<template>
  <div>
    <h2>current locale: {{ this.$i18n.locale }}</h2>
    <h2>brandName: {{ this.$route.params.brandName }}</h2>
    <h2>brandId: {{ this.$route.params.brandId }}</h2>

    <p>Try to refresh. <span style="color: red">ERR_TOO_MANY_REDIRECTS</span> error will be occured.</p>
    <p>No problem when move page with nuxt-link.</p>
    <p>No problem if remove ampersand(%26) from the url</p>
    <p>No problem if add locale that is not default locale to the url (<a href="http://localhost:3000/ko/apple-%26/1">http://localhost:3000/ko/apple-%26/1</a>)</p>


    Github question : <a href="https://github.com/nuxt-community/i18n-module/issues/1469">https://github.com/nuxt-community/i18n-module/issues/1469</a>
  </div>
</template>

<script>
export default {

}
</script>

<style>

</style>