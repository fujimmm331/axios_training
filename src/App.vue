<template lang="pug">
  v-app
    form-component
</template>

<script lang="ts">
import Vue from "vue";
import FormComponent from "./components/form.vue";


export default Vue.extend({
  name: "App",

  components: {
    FormComponent
  },

  data: () => ({
    //
  }),
});
</script>
