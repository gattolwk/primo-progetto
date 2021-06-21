<template>
  <div>
    <b-carousel
      id="carousel-fade"
      style="text-shadow: 0px 0px 2px #000"
      fade
      indicators
      img-width="1024"
      img-height="480"
    >
      <b-carousel-slide
        caption="Melodica"
        img-src="https://www.davidebonetti.it/wordpress/wp-content/uploads/2020/02/cropped-DSC_4877-scaled-2.jpg"
      ></b-carousel-slide>
      <b-carousel-slide
        caption="Anouk"
        img-src="https://www.davidebonetti.it/wordpress/wp-content/uploads/2021/03/vlcsnap-2021-03-02-12h06m59s736-520x347.png"
      ></b-carousel-slide>
      <b-carousel-slide
        caption="Disco"
        img-src="https://www.davidebonetti.it/wordpress/wp-content/uploads/2017/10/cover-pp1-4-ok-768x393.png"
      ></b-carousel-slide>
    </b-carousel>
  </div>
</template>

<script>
export default {
  name: "carosello"
}
</script>

<style scoped>

</style>
