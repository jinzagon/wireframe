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
<section class="text-blueGray-700 ">
      <div class="container flex flex-col items-center px-5 mx-auto">
         
      </div>

       <div id="app">
    <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div>
    <router-view/>
  </div>
    </section>

    <footer-component></footer-component>
  </div>
</template>

<script>
import MenuComponent from "./components/menu.vue"; 
import FooterComponent from "./components/footer.vue";

export default {
   
  name: "",
  components: {
    MenuComponent, 
    FooterComponent,
  },
};
</script>

<style></style>
