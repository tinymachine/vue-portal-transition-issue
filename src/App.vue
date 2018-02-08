<template>
  <div id="app">
    <the-modal-parent/>
    <portal-target name="modalDestination"/>
  </div>
</template>

<script>
import TheModalParent from './TheModalParent.vue'

export default {
  name: 'app',
  components: {
    TheModalParent
  }
}
</script>
