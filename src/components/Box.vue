<template>
  <div class="box has-text-weight-bold" :style="estilos">
    <slot></slot>
  </div>
</template>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  name: 'Box.vue',
  data () {
    return {
      estilos: {
        backgroundColor: '#FAF0CA'
      }
    }
  }
})
</script>
