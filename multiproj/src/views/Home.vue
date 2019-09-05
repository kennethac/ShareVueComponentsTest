<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Name />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Name from '../../../multiprojinner/src/components/Name.vue';

@Component({
  components: {
    Name
  }
})
export default class Home extends Vue {}
</script>
