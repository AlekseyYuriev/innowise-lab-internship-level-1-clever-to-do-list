<template>
  <div class="loader"></div>
</template>

<script>
export default {}
</script>

<style scoped>
.loader {
  width: 50px;
  aspect-ratio: 1;
  border-radius: 50%;
  background:
    radial-gradient(farthest-side, #fe8c2c 94%, #0000) top/8px 8px no-repeat,
    conic-gradient(#0000 30%, #fe8c2c);
  -webkit-mask: radial-gradient(farthest-side, #0000 calc(100% - 8px), #000 0);
  animation: l13 1s infinite linear;
}
@keyframes l13 {
  100% {
    transform: rotate(1turn);
  }
}
</style>
