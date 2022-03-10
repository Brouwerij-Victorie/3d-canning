<script setup>
import HelloWorld from "./components/HelloWorld.vue";
import TheWelcome from "./components/TheWelcome.vue";
</script>

<template>
  <model-viewer
    src="VIC_Croptop_WebCanTest-2.gltf"
    camera-controls
    ar
    ar-modes="scene-viewer webxr"
    class="can__viewer"
    skybox-image="aircraft_workshop_01_1k.hdr"
  ></model-viewer>
</template>

<style>
body {
  margin: 0;
  padding: 0;
}
.can__viewer {
  width: 100vw;
  height: 100vh;
}
</style>
