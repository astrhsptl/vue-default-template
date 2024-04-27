<script setup lang="ts">
import { defineComponent } from 'vue';
import Component from './Component.vue';
</script>

<script lang="ts">
export default defineComponent({
  data() {
    return {
      propData: {
        title: "asdfff"
      }
    };
  },
  methods: {},
  components: { Component }
})
</script>

<template>
  <Component v-bind="propData" />
</template>

<style scoped>
</style>
