<template>
  <!-- <Tutorial/> -->
  <div class="container">
    <div>
      <nuxt-link :to="localePath('about')">{{ $t('about') }}</nuxt-link>
      <nuxt-link :to="localePath('contact')">{{ $t('contact') }}</nuxt-link>
    </div>
    <div>
      <language-input />
    </div>
    <h1 class="title">{{ $t('message') }}</h1>
  </div>
</template>

<script>
</script>
