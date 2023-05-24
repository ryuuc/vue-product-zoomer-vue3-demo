<script setup>
import ScrollerAtBottom from "./components/examples/ScrollerAtBottom.vue";
import ScrollerAtTop from "./components/examples/ScrollerAtTop.vue";
import ScrollerAtRight from "./components/examples/ScrollerAtRight.vue";
import ScrollerAtLeft from "./components/examples/ScrollerAtLeft.vue";
import InsideRound from "./components/examples/InsideRound.vue";
import InsideContainer from "./components/examples/InsideContainer.vue";
</script>

<template>
   <div class="hero">
    <ScrollerAtTop />
    <hr class="hr" />
    <ScrollerAtLeft />
    <hr class="hr" />
    <ScrollerAtBottom />
    <hr class="hr" />
    <ScrollerAtRight />
    <hr class="hr" />
    <InsideRound />
    <hr class="hr" />
    <InsideContainer />
  </div>
</template>

<style scoped>
pre {
  padding: 0px !important;
}
</style>
