<template>
   <button class="p-2 bg-gray-400 m-3">{{ text }}</button>
</template>

<script>
export default {
  name: 'ButtonCom',
  props: {
    text: String
  }
}
</script>
