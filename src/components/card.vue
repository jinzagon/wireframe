<template>
 
     <div class=" lg:w-1/4">
                  <div class="p-6">
                   <img :src="image"
                
                class=" rounded-btn object-cover xl:h-60 xl:w-72 object-center w-full lg:h-48 md:h-36"
              /> <div class="inline-flex justify-between w-full mt-5">
                      <p class="mb-8  text-black  ">{{ description }}</p>
                      <span class="font-bold">${{ price }}</span>
                    </div>
                     </div>
                </div>
 
</template>

<script>
export default {
  props: {
    image: String,
    description: String,
    price: String,
  }
}
</script> 