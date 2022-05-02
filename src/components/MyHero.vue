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
.jumbo {
  position: relative;
}
h2 {
  color: white;
  margin: 40px 0 0;
  font-size: 4rem;
  background-color: rgba(0, 0, 0, 0.575);
  border-radius: 10px;
  padding: 1rem;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
img {
  margin-top: 2rem;
  max-width: 50%;
}
</style>