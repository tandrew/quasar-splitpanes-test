<template>
  <q-page class="flex flex-center">
    <img alt="Quasar logo" src="~assets/quasar-logo-full.svg">

    <splitpanes class="default-theme" horizontal :push-other-panes="false" style="height:400px">
      <span>1</span>
      <splitpanes :push-other-panes="false">
        <span>2</span>
        <span>3</span>
        <span>4</span>
      </splitpanes>
      <span>5</span>
    </splitpanes>
  </q-page>
</template>

<style>
</style>

<script>
import Splitpanes from 'splitpanes'
import 'splitpanes/dist/splitpanes.css'

export default {
  name: 'PageIndex',
  components: {
    Splitpanes
  }
}
</script>
