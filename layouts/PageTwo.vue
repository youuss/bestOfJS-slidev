<template>
  <div class="slidev-layout page-two">
    <slot />
  </div>
</template>

<style lang="postcss">
.slidev-layout.page-two {
  background-image: url("../assets/page-2.svg");
  background-repeat: no-repeat;
  background-position: center;
  background-size: cover;
  padding: 2em 5em;
}
</style>
