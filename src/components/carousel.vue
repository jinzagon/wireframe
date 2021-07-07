<template>
  <div class="mt-14">
    <VueSlickCarousel :arrows="false" :dots="true">
      <div><h1 class="custom text-5xl font-bold  w-96 fixed text-white p-10 pl-16">Suspendisse interdum rutrum nise</h1><p  class="font-light text-white pl-16 txt-small">Ut tellus quam, venenatis non tempus, volupat blandit.</p><img src="https://spacejob.co.jp/wp-content/uploads/2021/03/revolt-164_6wVEHfI-unsplash-1024x683.jpg" class=" rounded-btn object-cover h-96 w-screen mx-auto px-6 rounded-lg"></div>
      <div><h1 class="custom text-5xl font-bold  w-96 fixed text-white p-10 pl-16">Suspendisse interdum rutrum nise</h1><p  class="font-light text-white pl-16 txt-small">Ut tellus quam, venenatis non tempus, volupat blandit.</p><img src="https://sneakernews.com/wp-content/uploads/2019/06/nike-air-max-1-independence-day-cj4283-100-3.jpg" class=" rounded-btn object-cover h-96 w-screen mx-auto px-6 rounded-lg"></div>
      <div><h1 class="custom text-5xl font-bold  w-96 fixed text-white p-10 pl-16">Suspendisse interdum rutrum nise</h1><p  class="font-light text-white pl-16 txt-small">Ut tellus quam, venenatis non tempus, volupat blandit.</p><img src="https://static.highsnobiety.com/thumbor/PrBQpd2hh7cVJ45B7oH8n5u4lR8=/1600x1067/static.highsnobiety.com/wp-content/uploads/2020/03/26164116/underrated-nike-air-max-sneakers-buy-here-05.jpg" class=" rounded-btn object-cover h-96 w-screen mx-auto px-6 rounded-lg"></div>
      
    </VueSlickCarousel>
  </div>
</template>

<script>
  import VueSlickCarousel from 'vue-slick-carousel'
  import 'vue-slick-carousel/dist/vue-slick-carousel.css'
  // optional style for arrows & dots
  import 'vue-slick-carousel/dist/vue-slick-carousel-theme.css'
 
  export default {
    name: 'MyComponent',
    components: { VueSlickCarousel },
  }
</script> 