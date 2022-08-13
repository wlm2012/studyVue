<template>
  <div class="home">
    <a-button type="primary" :size="size">Primary</a-button>
    <a-button :size="size">Normal</a-button>
    <a-button type="dashed" :size="size">Dashed</a-button>
    <a-button danger :size="size">Danger</a-button>
    <a-button type="link" :size="size">Link</a-button>
    <br />
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js + TypeScript App"/>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue';
import HelloWorld from '@/components/HelloWorld.vue'; // @ is an alias to /src

export default defineComponent({
  name: 'HomeView',
  components: {
    HelloWorld,
  },
});
</script>
