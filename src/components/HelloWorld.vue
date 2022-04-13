<template>
  <div class="flex">
    <h1>{{ msg }}</h1>
    <Button text="add" />
  </div>
</template>

<script>
import Button from './ButtonCom.vue'

export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  components: {
    Button
  }
}
</script>
