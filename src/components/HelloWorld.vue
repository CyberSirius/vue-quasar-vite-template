<template>
  <h1>{{ msg }}</h1>


  <p></p>
  <q-btn type="button" @click="count++">count is: {{ count }}</q-btn>
  <p>
    Edit
    <code>components/HelloWorld.vue</code> to test hot module replacement.
  </p>
</template>
<script lang="ts" setup>
import {ref} from 'vue'

defineProps<{
  msg: string
}>()


const count = ref(0)
</script>

<style scoped>
a {
  color: #42b983;
}
</style>
