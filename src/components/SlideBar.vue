<template>
  <div>
    <div class="slide-bar-left">
      <slot name="slide"></slot>
      <a>test</a>
    </div>
    <div class="slide-bar-right">
      <slot name="content"></slot>
    </div>
  </div>
</template>

<script>

</script>

<style lang="scss">
  .slide-bar-left {
    width: 660px;

    a {
      color: red;
    }
  }
</style>