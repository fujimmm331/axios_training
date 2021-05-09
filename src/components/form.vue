<template lang="pug">
  div#form
    v-card-title
      h1 住所検索
    v-card-text
      p 郵便番号を入力することで、住所を検索できます。
      v-form
        v-text-field(
          prepend-icon="mdi-magnify",
          label="例）2400006",
          width="80%")
      v-card-actions
        v-btn 検索
</template>
<script lang="ts">
import { defineComponent } from "@vue/composition-api";
export default defineComponent({
  // setup() {
  // },
});
</script>
<style scoped>
</style>
