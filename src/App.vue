<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <model-viewer
    class="can__viewer"
    src="VIC_Croptop_WebCanTest-2.gltf"
    camera-controls
    ar
    ar-scale="fixed"
    skybox-image="aircraft_workshop_01_1k.hdr"
    ios-src="VIC_Croptop_WebCanTest-2.usdz"
    xr-environment
    width="100px"
    height="100px"
  ></model-viewer>
</template>

<style>
body {
  overflow: hidden;
  margin: 0;
  padding: 0;
}
.can__viewer {
  position: relative;
  width: 50vw;
  height: 50vw;
}
</style>
