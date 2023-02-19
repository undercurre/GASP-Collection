<template>
  <div
    class="box"
    @click="handle"
  >
    动画
  </div>
</template>

<script lang="ts" setup>
import gsap from 'gsap'

function handle() {
  gsap.fromTo(".box", {autoAlpha: 0}, {autoAlpha: 0.5, duration: 1});
}
</script>
<style>
/* styles emitted */
</style>
