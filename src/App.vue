<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3.0 + Vite" />
  <a-button type="primary"> Primary </a-button>
</template>

<script>
import { Button } from 'ant-desigin-vue'
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
  },
}
</script>
