<template>
  <p>Hello {{ name }}</p>
</template>

<script lang="ts">
import { Component, Prop, Vue } from "vue-property-decorator";

@Component
export default class Name extends Vue {
  get name() {
    return this.$store.state.name;
  }
}
</script>