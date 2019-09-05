<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <Name />
  </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import Name from '@/components/Name.vue' // @ is an alias to /src

@Component({
  components: {
    Name
  }
})
export default class Home extends Vue {}
</script>
