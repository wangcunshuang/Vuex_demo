<template>
  <div class="app-container">
    <h1>App 根组件</h1>
    <addition></addition>
    <p>--------------------------------------</p>
    <subtraction></subtraction>
  </div>
</template>

<script>
import Addition from './components/Addition.vue'
import Subtraction from './components/Subtraction.vue'
export default {
  data () {
    return {

    }
  },
  components: {
    Addition,
    Subtraction
  }
}
</script>

<style>

</style>
