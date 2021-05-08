<template lang="pug">
  v-app
    form-component
    table-component
</template>

<script lang="ts">
import Vue from "vue";
import FormComponent from "./components/form.vue";
import TableComponent from "./components/table.vue";


export default Vue.extend({
  name: "App",

  components: {
    FormComponent,
    TableComponent
  },

  data: () => ({
    //
  }),
});
</script>
