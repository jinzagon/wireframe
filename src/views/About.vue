<template>
  <div class="about">
    <div class="flex-col w-full md:flex md:flex-row md:min-h-screen bg-blueGray-50">
            <div class="flex flex-col flex-shrink-0 w-full bg-white shadow-xl text-blueGray-700 md:w-64">
              <div class="flex flex-row items-center justify-between flex-shrink-0 py-4">
                <a href="/" class="px-8 focus:outline-none">
                  <div class="inline-flex items-center">
                    <div class="w-2 h-2 p-2 mr-2 rounded-full bg-gradient-to-tr from-blue-500 to-blue-600">
                    </div>
                    <h2 class="block p-2 text-xl font-medium tracking-tighter text-black transition duration-500 ease-in-out transform cursor-pointer hover:text-blueGray-500 lg:text-x lg:mr-8"> wickedblocks </h2>
                  </div>
                </a>
                <button class="rounded-lg md:hidden focus:outline-none focus:shadow-outline">
                  <svg fill="currentColor" viewBox="0 0 20 20" class="w-6 h-6">
                    <path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM9 15a1 1 0 011-1h6a1 1 0 110 2h-6a1 1 0 01-1-1z" clip-rule="evenodd"></path>
                    <path fill-rule="evenodd" d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" clip-rule="evenodd"></path>
                  </svg>
                </button>
              </div>
              <nav class="flex-grow pb-4 pr-4 md:block md:pb-0 md:overflow-y-auto">
                <ul>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-blue-600 text-blueGray-500 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">Prices</a>
                  </li>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-white text-blueGray-500 hover:border-blue-600 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">Contact</a>
                  </li>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-white text-blueGray-500 hover:border-blue-600 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">Services</a>
                  </li>
                  <li>
                    <a class="block px-4 py-2 mt-2 text-base transition duration-500 ease-in-out transform border-l-4 border-white text-blueGray-500 hover:border-blue-600 focus:shadow-outline focus:outline-none focus:ring-2 ring-offset-current ring-offset-2 hover:text-black" href="#">Services</a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>




            <div class="flex-none md:flex xl:flex lg:flex">
  
    

 <card-component 
   v-for="(item, key) in products"
        :key="key"
          :description="item.description"
          :price="item.price"
          :image="item.img"
        ></card-component>

   
     
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
