<template>
  <div class="container">
    <div>
      <nuxt-link :to="localePath('index')">{{ $t('home') }}</nuxt-link>
      <nuxt-link :to="localePath('about')">{{ $t('about') }}</nuxt-link>
      <nuxt-link :to="localePath('contact')">{{ $t('contact') }}</nuxt-link>
    </div>
    <div>
      <language-input />
    </div>
    <Nuxt />
  </div>
</template>

<script>
export default {};
</script>

<style></style>
