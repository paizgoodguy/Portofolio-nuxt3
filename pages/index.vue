<template>
  <div>
    <Introduction />
    <About />
    <WebProjects />
    <!-- <OtherSkills /> -->
    <Footer />
  </div>
</template>

<script setup></script>

<style>
.screen-center {
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  position: fixed;
}

.screen-center-full {
  width: 100vh;
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
}

.page {
  height: 100vh;
  width: 100%;
}

/* .page-enter-active,
.page-leave-active {
  transition: opacity 0.3s;
}

.page-enter,
.page-leave-active {
  opacity: 0.5;
} */

/* #container {
  scroll-snap-type: y mandatory;
}

section {
  scroll-snap-align: start;
  
} */
</style>
