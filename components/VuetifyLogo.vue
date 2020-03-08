<template>
  <img class="VuetifyLogo" alt="Vuetify Logo" src="/v.png" />
</template>

<style>
.VuetifyLogo {
  width: 180px;
  transform: rotateY(560deg);
  animation: turn 2s ease-out forwards 1s;
}

@keyframes turn {
  100% {
    transform: rotateY(0deg);
  }
}
</style>
