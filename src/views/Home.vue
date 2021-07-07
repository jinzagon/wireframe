<template>
  <div class="home">
       
       
<carousel-component></carousel-component>

    <section class="text-blueGray-700 ">
      <div class="items-center py-8 mx-auto lg:px">
        <div class="flex flex-wrap mb text-left">
          <div class="w-full mx-auto lg:w-1/3">
            <div class="p-6">
              <img
                class="object-cover object-center w-full mb-8 lg:h-48 md:h-36"
                src="https://dummyimage.com/720x400/F3F4F7/8693ac"
                alt="blog"
              />
            </div>
          </div>
          <div class="w-full mx-auto lg:w-1/3">
            <div class="p-6">
              <img
                class="object-cover object-center w-full mb-8 lg:h-48 md:h-36"
                src="https://dummyimage.com/720x400/F3F4F7/8693ac"
                alt="blog"
              />
            </div>
          </div>
          <div class="w-full mx-auto lg:w-1/3">
            <div class="p-6">
              <img
                class="object-cover object-center w-full mb-8 lg:h-48 md:h-36"
                src="https://dummyimage.com/720x400/F3F4F7/8693ac"
                alt="blog"
              />
            </div>
          </div>
        </div>
      </div>
    </section>

    <section class="text-blueGray-700 ">
      <div class="container flex flex-col items-center px-5 mx-auto">
        <div class="flex flex-col w-full  text-left lg:text-center">
          <h1
            class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-black lg:w-1/2 lg:text-3xl title-font custom custom-color"
          >
            Featured products
          </h1>
        </div>
      </div>
    </section>
    <section>
      <div class="flex-none md:flex xl:flex lg:flex ">
        <card-component
          description="Vestibulum tincidunt a metus hendrer"
          price="23.23"
          image="https://spacejob.co.jp/wp-content/uploads/2021/03/revolt-164_6wVEHfI-unsplash-1024x683.jpg"
        ></card-component>
        <card-component
          description="Lorem ipsum dolor sit amet, consectetur adipiscing elit"
          price="43.44"
          image="https://sneakernews.com/wp-content/uploads/2019/06/nike-air-max-1-independence-day-cj4283-100-3.jpg"
        ></card-component>
        <card-component
          description="Sed ut perspiciatis unde omnis iste "
          price="68.96"
          image="https://media.gucci.com/style/DarkGray_Center_0_0_490x490/1521230410/524990_DRW00_9022_006_100_0000_Light-Womens-Rhyton-glitter-Gucci-sneaker.jpg"
        ></card-component>
        <card-component
          description="Ut enim ad minima veniam, quis nostrum exercitationem "
          price="43.44"
          image="https://static.highsnobiety.com/thumbor/PrBQpd2hh7cVJ45B7oH8n5u4lR8=/1600x1067/static.highsnobiety.com/wp-content/uploads/2020/03/26164116/underrated-nike-air-max-sneakers-buy-here-05.jpg"
        ></card-component>
      </div>
    </section>

<div class="container flex flex-col items-center px-5 mx-auto">
        <div class="flex flex-col w-full  text-left lg:text-center">
           <h1
            class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-black lg:w-1/2 lg:text-2xl title-font custom custom-color"
          >
            <router-link to="/about">View All</router-link>
 
          </h1> 

           
        </div>
      </div>

  </div>
</template>

<script>
// @ is an alias to /src
import CardComponent from '@/components/card.vue'; 
import CarouselComponent from "@/components/carousel.vue"; 

export default {
  name: 'Home',
  components: { 
    CardComponent,
    CarouselComponent,
  }
}
</script>
