<template>
 
     <div class=" ">
                  <div class="p-6">
                   <img :src="image"                
                class=" rounded-btn object-cover h-60 w-full object-center w-full lg:h-48 md:h-36"
              /> <div class="inline-flex justify-between w-full mt-5">
                      <p class="mb-8  text-black  ">{{ description }}</p>
                      <span class="font-bold">${{ price }}</span>
                    </div>
                    <div class="justify-center card-actions"><button v-on:click="increment" class="btn btn-sm btn-accent normal-case mx-3 border-0" style="background-color:#ce071e">Add to Cart</button></div>
                       <div>{{ items }} {{ counter }} </div>
                     </div>
                </div>
 
</template>

<script>
export default {
    data() { return { counter: 0}
     
    },
    methods: {
      increment() { 
        this.counter++;
      }
    },
  props: {
    image: String,
    description: String,
    price: String,
  }
}



</script> 