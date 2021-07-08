<template>
 
     <div class=" ">
                  <div class="p-6">
                   <router-link to="/detail"><img :src="image"                
                class=" rounded-btn object-cover h-60 w-full object-center w-full lg:h-60 md:h-36"
              /></router-link> <div class="inline-flex justify-between w-full mt-5">
                      <p class="mb-8 pr-2 text-black  ">{{ description }}</p>
                      <span class="font-bold">${{ price }}</span>
                    </div>
                    <div class="justify-center card-actions"><button v-on:click="$emit('increment')" class="btn btn-sm btn-accent normal-case mx-3 border-0" style="background-color:#ce071e">Add to Cart</button></div>
                       <div>{{ items }} </div>
                     </div>
                     
                </div>
 
</template>

<script>
export default {
    data() { return { cardMessage: ''}
     
    },
    methods: {
    emitToParent (event) {
      this.$emit('cardToParent', this.cardMessage)
    }
  },
  props: {
    image: String,
    description: String,
    price: String,
  }
}



</script> 