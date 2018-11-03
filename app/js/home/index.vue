<template lang="html">
    <div :class="$style.home">
        <h1>Home</h1>
        <h2 :class="$style.test">123132</h2>
    </div>
</template>

<script>
export default {
}
</script>

<style lang="scss" module>
  @import '../../css/reset.scss';
  .home{
    color : orange;
    font-size: 80px;
  }
  .test{
    color : red;
    font-size: 40px;
  }
</style>
