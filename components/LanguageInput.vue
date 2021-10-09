<template>
  <div class="lang-dropdown">
    <select v-model="$i18n.locale" @change="setLocale">
      <option v-for="lang in $i18n.locales" :key="lang.code" :value="lang.code">
        {{ lang.name }}
      </option>
    </select>
  </div>
</template>

<script>
export default {
  methods: {
    setLocale() {
      // console.log(`Locale: ${this.$i18n.locale}`);
      // localStorage.setItem('locale', this.$i18n.locale);
    },
  },
};
</script>

<style></style>
