<template>
    <DemoWorld>
        <ul class="w-64 text-center font-bold text-xl">
            <li>01</li>
            <li>02</li>
            <li>03</li>
        </ul>
    </DemoWorld>
</template>

<script lang="ts">
import { defineComponent } from 'vue'
import DemoWorld from './components/DemoWorld.vue'

export default defineComponent({
  name: 'App',
  components: {
    DemoWorld: DemoWorld
  }
})
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>