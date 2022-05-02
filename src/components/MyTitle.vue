<template>
  <div class="title">
    <h1>{{ msg_title }}</h1>
  </div>
</template>

<script>
export default {
  name: 'MyTitle',
  props: {
    msg_title: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h1 {
  color: cornflowerblue;
  margin: 40px 0 0;
}
</style>
