<template>
  <div class="jumbo">
    <h2>{{ titleHero }}</h2>
    <img src="https://images.everyeye.it/img-articoli/it-capitolo-2-recensione-dell-ultra-hd-blu-ray-4k-dolby-vision-v7-46698.jpg" alt="">
  </div>
</template>

<script>
export default {
  name: 'MyHero',
  props: {
    titleHero: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
h2 {
  color: cornflowerblue;
  margin: 40px 0 0;
}
img {
  max-width: 50%;
}
</style>