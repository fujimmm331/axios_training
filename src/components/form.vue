<template lang="pug">
  div#form
    v-card-title
      h1 住所検索
    v-card-text
      p 郵便番号を入力することで、住所を検索できます。
      v-form
        v-text-field(
          v-model="form.text",
          autofocus=true,
          prepend-icon="mdi-magnify",
          label="例）2400006",
        )
      v-card-actions
        v-btn(
          @click="onSearch"
        ) 検索
</template>
<script lang="ts">
import { defineComponent, reactive } from '@vue/composition-api';

export interface State {
  text: string;
}

export default defineComponent({
  setup() {
    const form = reactive<State>({
      text: '',
    });
    const onSearch = () => {
      console.log(form.text);
    };
    return {
      form,
      onSearch,
    };
  },
});
</script>
<style scoped></style>
