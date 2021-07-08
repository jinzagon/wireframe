<template>
  <div class="about">
    <div class="p-6">
      <nav class="text-black font-bold my-2 text-sm" aria-label="Breadcrumb">
  <ol class="list-none p-0 inline-flex">
    <li class="flex items-center">
      <router-link to="/">Home</router-link>
      <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
    </li> 
     <li class="flex items-center">
      <router-link to="/about">Shoes Category</router-link>
      <svg class="fill-current w-3 h-3 mx-3" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 320 512"><path d="M285.476 272.971L91.132 467.314c-9.373 9.373-24.569 9.373-33.941 0l-22.667-22.667c-9.357-9.357-9.375-24.522-.04-33.901L188.505 256 34.484 101.255c-9.335-9.379-9.317-24.544.04-33.901l22.667-22.667c9.373-9.373 24.569-9.373 33.941 0L285.475 239.03c9.373 9.372 9.373 24.568.001 33.941z"/></svg>
    </li> 
    <li>
      <a href="#" class="text-gray-500" aria-current="page">Detail</a>
    </li>
  </ol>
</nav>
       </div>
    

<section class="text-blueGray-700 ">
            <div class="flex flex-col items-start px-5 py-16 mx-auto lg:items-center md:flex-row lg:px-28">
              <div class="w-full mb-10 lg:w-5/6 lg:max-w-lg md:w-1/2">
                <img class=" rounded-btn object-cover h-72 w-full object-center w-full lg:h-72 md:h-72" alt="hero" loading="lazy" src="https://source.unsplash.com/user/kimboslice305/likes/16freaze">
              </div>
              <div class="flex flex-col items-center text-center lg:flex-grow md:w-1/2 lg:pl-5 md:pl-5 md:items-start md:text-left">
                 <h1 class="mb-3 text-2xl font-bold tracking-tighter text-left text-black lg:text-5xl custom">50z Frozen Yogurt Cups</h1>
                 <p class="mb-8 text-xl leading-relaxed text-left text-blueGray-700 border-b-2 w-full ">Lorem ipsun dolor sir amet</p>
                
       


                <div class="flex flex-wrap -mx-4 -mt-4 -mb-10 sm:-m-4 ">
                  <div class="flex flex-col items-start mb-4 text-left lg:flex-grow md:w-2/3 lg:pl-5">
                    

                    
                    <div class="flex-grow">
                       <p class="my-8 text-base leading-relaxed text-left text-blueGray-700 ">Perfect for frozen yogurt and other uses. Designed to hold both hot and cold items.</p>
                        <p class="my-8 text-base font-semibold leading-relaxed text-left text-blueGray-700 ">Packaged in 1,000 cups per case. <br/>Standard Double PE coating.</p>

<div class="bg-red-300 w-2/3 h-auto text-center py-5"><span class="custom font-bold">Custom Print Service Available.</span>
   <button class="btn btn-xs px-7  normal-case rounded-sm bg-red-500 border-0 uppercase mt-3">Learn More</button>
</div>

<br/>This yogurt cup / food container is biodegradablre and part of our commitment to environmental friendly disposable takeout products. 


                    </div>
                  </div>
                  <div class="flex flex-col items-start mb-4 text-left lg:flex-grow md:w-1/3 lg:pl-10">
                    <div class="inline-flex items-center justify-center flex-shrink-0 w-12 h-12 mb-5 text-black rounded-full bg-blueGray-50">
                       
                    </div>
                    <div class="flex-grow">
                      <h2 class="mb-3 text-lg font-bold tracking-tighter text-blueGray-700 custom">Price: 119$</h2>
                       <h2 class="mb-3 text-lg font-bold tracking-tighter text-blueGray-700 custom">Quantity: </h2>
                        <h2 class="mb-3 text-lg font-bold tracking-tighter text-blueGray-700"><span class="custom">Color:</span>White</h2>
                    <button class="btn px-7  normal-case rounded-sm bg-red-500 border-0  mt-3 text-lg custom">Add to Cart</button> 
                    </div>

                    
                  </div>
                 
                   
                </div>
              </div>
            </div>
          </section>


            




  
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
