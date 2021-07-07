<template>
  <div>
    <!--<div class="items-center h-8" style="background-color:#cbe3e6">
            <div class="items-center justify-between w-full px-5 overflow-y-auto tflex whitespace-nowrap scroll-hidden ">
              <div class="flex flex-col flex-wrap mx-auto md:items-center md:flex-row">
                <a href="/" class="pr-2 lg:pr-8 lg:px-6 focus:outline-none">
                  <div class="inline-flex items-center">
                    <div class="w-2 h-2 p-2 mr-2 rounded-full bg-gradient-to-tr from-blue-500 to-blue-600">
                    </div>
                    <h2 class="block p-2 text-xl font-medium tracking-tighter text-black transition duration-500 ease-in-out transform cursor-pointer hover:text-blueGray-500 lg:text-x lg:mr-8"> wickedblocks </h2>
                  </div>
                </a>
                <nav class="flex flex-wrap items-center justify-start text-base ">
                  <ul class="items-center inline-block list-none lg:inline-flex">
                    <li>
                      <a href="#" class="px-4 py-1 mr-1 text-base text-blueGray-500 transition duration-500 ease-in-out transform rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black ">About</a>
                    </li>
                    <li>
                      <a href="#" class="px-4 py-1 mr-1 text-base text-blueGray-500 transition duration-500 ease-in-out transform rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black ">Partner Program</a>
                    </li>
                    <li>
                      <a href="#" class="px-4 py-1 mr-1 text-base text-blueGray-500 transition duration-500 ease-in-out transform rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black ">Franchise</a>
                    </li>
                    <li>
                      <a href="#" class="px-4 py-1 mr-1 text-base text-blueGray-500 transition duration-500 ease-in-out transform rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black ">How to Order</a>
                    </li>
                     <li>
                      <a href="#" class="px-4 py-1 mr-1 text-base text-blueGray-500 transition duration-500 ease-in-out transform rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black ">Contact</a>
                    </li>
                  </ul>
                </nav>
                <button class="w-auto px-8 py-2 my-2 ml-auto text-base font-medium text-white transition duration-500 ease-in-out transform bg-blue-600 border-blue-600 rounded-md focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:b-gblue-700">Button </button>
              </div>
            </div>
          </div>-->
    <div
      class=" items-center  h-8 hidden md:hidden xl:block lg:block text-xs text-white"
      style="background-color: #ce071e;"
    >
      <div class="text-blueGray-700 rounded-lg">
        <div
          class="flex flex-col flex-wrap mx-auto md:items-center md:flex-row"
        >
          <a href="/" class="pr-2 lg:pr-8 lg:px-6 focus:outline-none">
            <div class="inline-flex items-center"></div>
          </a>

          <ul
            class="float-left items-center inline-block list-none lg:inline-flex mt-1 mr-auto "
          >
            Social Media sharing links
          </ul>

          <ul
            class="items-center inline-block list-none lg:inline-flex mt-1 ml-auto"
          >
            <li>
              <a href="#" class="  py-1 mr-1 text-sm">Login |</a>
            </li>
            <li>
              <a href="#" class="  py-1 mr-1 text-sm">Register</a>
            </li>
          </ul>

          <ul
            class="items-center inline-block list-none lg:inline-flex mt-1 ml-12 mr-12"
          >
            <li>
              <a href="#" class="  py-1 mr-1 text-sm font-semibold"
                >0 items |</a
              >
            </li>
            <li>
              <a href="#" class="  py-1 mr-1 text-sm">Checkout</a>
            </li>
          </ul>

          <ul
            class="items-center inline-block list-none lg:inline-flex mt-1 pr-6"
          >
            <li>
              <a href="#" class="px-2 py-1 mr-1 text-sm">About</a>
            </li>
            <li>
              <a href="#" class="px-2 py-1 mr-1 text-sm">Partner Program</a>
            </li>
            <li>
              <a href="#" class="px-2 py-1 mr-1 text-sm">Franchise</a>
            </li>
            <li>
              <a href="#" class="px-2 py-1 mr-1 text-sm">How to Order</a>
            </li>
            <li>
              <a href="#" class="px-2 py-1 mr-1 text-sm">Contact</a>
            </li>
          </ul>
        </div>
      </div>
    </div>

    <div class="mx-auto">

    <menu-component></menu-component>


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

    <section class="text-blueGray-700 ">
      <div class="container flex flex-col items-center px-5 mx-auto">
        <div class="flex flex-col w-full  text-left lg:text-center">
          <h1
            class="mx-auto mb-8 text-2xl font-semibold leading-none tracking-tighter text-black lg:w-1/2 lg:text-2xl title-font custom custom-color"
          >
            View All
          </h1>
        </div>
      </div>
    </section>

    <!--<div class="caSrd w-1/4">
      <div class="bg-indigo-300 p-7">
        <img
          src="https://spacejob.co.jp/wp-content/uploads/2021/03/revolt-164_6wVEHfI-unsplash-1024x683.jpg"
          class=" rounded-btn object-cover h-60 w-72"
        />
        <div class="content flex mt-4"><p class="w-8/12"> Vestibulum tincidunt tellus a metus hendrer </p><p class=" w-3/6 items-start text-right font-bold text-lg" style="direction: rtl;"> 199.23 $ </p></div>
        <div class="justify-center card-actions"><button class="btn btn-sm btn-accent normal-case  btn-success   mx-3">Add to Cart</button></div>
      </div>
    </div>-->

    </div>

    <footer-component></footer-component>
  </div>
</template>

<script>
import MenuComponent from "./components/menu.vue";
import CarouselComponent from "./components/carousel.vue";
import CardComponent from "./components/card.vue";
import FooterComponent from "./components/footer.vue";

export default {
  name: "",
  components: {
    MenuComponent,
    CarouselComponent,
    CardComponent,
    FooterComponent,
  },
};
</script>

<style></style>
