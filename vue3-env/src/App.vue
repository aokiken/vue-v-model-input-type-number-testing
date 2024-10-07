<template>
  <div id="app">
    <h2>Vue 3({{ version }})</h2>
    <input type="number" v-model="value">
    <p>値は {{ typeof value }} 型です。</p>
    <p>value: {{ value }}</p>
  </div>
</template>
<script>
import { version } from 'vue'
export default {
  name: 'App',
  data(){
    return {
      value: '',
      version,
    }
  },
}
</script>
