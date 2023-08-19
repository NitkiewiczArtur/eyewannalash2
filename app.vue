<template>
  <div class="main">
    <NuxtPage/>
  </div>
</template>
<style lang="scss">
.main {
  margin: 0;
  padding: 0;
  height: 100dvh;
  display: flex;
  flex-direction: column;
}

.full-height {
  flex: 1;
}
.page-enter-active,
.page-leave-active {
  transition: all 0.4s;
}
.page-enter-from,
.page-leave-to {
  opacity: 0;
  filter: blur(1rem);
}
</style>
