<template>
  <div class="slidev-layout page-one">
    <slot />
  </div>
</template>

<style lang="postcss">
.slidev-layout.page-one {
  background-image: url("../assets/page-1.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  padding: 2em 5em;
}
</style>
