<template>
  <div class="about">
    <div class="p-6">
      <nav class="text-black font-bold my-2 text-sm" aria-label="Breadcrumb">
  <ol class="list-none p-0 inline-flex">
    <li class="flex items-center">
      <router-link to="/">Home</router-link>
      <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
    </li> 
    <li>
      <a href="#" class="text-gray-500" aria-current="page">Shoes Category</a>
    </li>
  </ol>
</nav>
      <h1 class="custom text-5xl font-bold text-white absolute p-10 pl-16">Shoes Category</h1> <img class=" rounded-btn object-cover h-36 w-screen object-center" src="https://images.unsplash.com/photo-1516478177764-9fe5bd7e9717?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=750&q=80" >
    </div>
    <div class="flex-col w-full md:flex md:flex-row md:min-h-screen bg-blueGray-50">
            <div class="flex flex-col flex-shrink-0 w-full bg-white shadow-xl text-blueGray-700 md:w-64">
              <div class="flex flex-row items-center justify-between flex-shrink-0 py-4">
                <a href="/" class="px-8 focus:outline-none">
                  
                </a>
                
              </div>
              <nav class="flex-grow pb-4 pr-4 md:block md:pb-0 md:overflow-y-auto">
                <ul>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-red-600 text-blueGray-500 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">FILTER NAME</a>
                  <p>Option One</p>
                  <p>Second Option</p>
                  <p>And Another</p>
                  <p>Last Option</p>
                  </li>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-white text-blueGray-500 hover:border-red-600 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">FILTER NAME</a>
                   <p>Option One</p>
                  <p>Second Option</p>
                  <p>And Another</p>
                  <p>Last Option</p>
                  </li>
                   
                </ul>
              </nav>
            </div>

<div class="flex flex-wrap md:flex xl:flex lg:flex">
  
    
 
 <card-component 
   v-for="(item, key) in products"
        :key="key"
        class="lg:w-1/3"
          :description="item.description"
          :price="item.price"
          :image="item.img"
        ></card-component>

   
     
  </div>



          </div>




            




  
  </div>
</template>


<script>
import itemlist from "/itemlist.json";
import CardComponent from '@/components/card.vue';  

export default {
  data() {
    return {
      products: itemlist.items,
    };
  },
  methods: {
  },
  components: { 
    CardComponent,
  }
};
</script>
