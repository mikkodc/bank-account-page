<template lang="html">
  <header>
    <h1>{{ pageTitle }}</h1>
  </header>
</template>

<script>
export default {
  props: ['pageTitle']
};
</script>

<style lang="scss" scoped>
header {
  background: #11625a;
  box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.25);
  padding-top: 50px;
  padding-bottom: 20px;

  h1 {
    color: #ffff;
    font-size: 1.5em;
    text-align: center;
    font-weight: bold;
    margin-bottom: 0;
  }
}
</style>
