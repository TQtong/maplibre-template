<script setup lang="ts">
import {onMounted} from 'vue'

import { init } from './index'

onMounted(() => {
  init('map')
})

</script>

<template>
  <div id="container">
    <div id="map"></div>
  </div>
</template>

<style scoped lang="scss">
#container {
  width: 100%;
  height: 100%;
  #map {
    width: 100%;
    height: 100%;
  }
}
</style>
