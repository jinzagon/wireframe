<template>
  <div>
    <div class="bg-white drawer">
      <input id="my-drawer-3" type="checkbox" class="drawer-toggle" />
      <div class="flex flex-col drawer-content">
        <div class="w-full navbar bg-white">
          <div class="flex-none lg:hidden">
            <label for="my-drawer-3" class="btn btn-square btn-ghost">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                fill="none"
                viewBox="0 0 24 24"
                class="inline-block w-6 h-6 stroke-current"
              >
                <path
                  stroke-linecap="round"
                  stroke-linejoin="round"
                  stroke-width="2"
                  d="M4 6h16M4 12h16M4 18h16"
                ></path>
              </svg>
            </label>
          </div>
            
          <div class="flex-1 px-2 mx-2 mt-10">
            
            <span>
               <a class="flex title-font font-medium items-center md:justify-start justify-center text-gray-900">
        <svg xmlns="http://www.w3.org/2000/svg" fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" class="w-10 h-10 text-white p-2 bg-red-500 rounded-full" viewBox="0 0 24 24">
          <path d="M12 2L2 7l10 5 10-5-10-5zM2 17l10 5 10-5M2 12l10 5 10-5"></path>
        </svg>
        <span class="ml-3 text-5xl font-bold custom-color custom">InterGreen</span>
       
      </a>
        <span class="ml-3 text-sm float-right">DISTRIBUTORS</span>
            </span>
          </div>
          
          <div class="flex-none hidden lg:block">

          <div class="relative p-5"><input type="text" name="search" class=" w-52 h-8 bg-gray-100 bg-opacity-50 rounded border border-gray-300 focus:bg-transparent focus:ring-2 focus:ring-indigo-200 focus:border-indigo-500 text-base outline-none text-gray-700 py-1 px-3 leading-8 transition-colors duration-200 ease-in-out float-right">
          <button type="submit" class="absolute right-4 top-4 mt-3 mr-4">
    <svg class="h-4 w-4 fill-current" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px" viewBox="0 0 56.966 56.966" style="enable-background:new 0 0 56.966 56.966;" xml:space="preserve" width="512px" height="512px">
      <path d="M55.146,51.887L41.588,37.786c3.486-4.144,5.396-9.358,5.396-14.786c0-12.682-10.318-23-23-23s-23,10.318-23,23  s10.318,23,23,23c4.761,0,9.298-1.436,13.177-4.162l13.661,14.208c0.571,0.593,1.339,0.92,2.162,0.92  c0.779,0,1.518-0.297,2.079-0.837C56.255,54.982,56.293,53.08,55.146,51.887z M23.984,6c9.374,0,17,7.626,17,17s-7.626,17-17,17  s-17-7.626-17-17S14.61,6,23.984,6z"/>
    </svg>
  </button>
          </div>

            <ul class="menu horizontal uppercase">
              
              <li>
                <a class="rounded-btn text-lg custom-color" >Cups</a>
              </li>
              <li>
                <a class="rounded-btn text-lg custom-color">Spoons</a>
              </li>
              <li>
                <a class="rounded-btn text-lg custom-color">Lids</a>
              </li>
              <li>
                <a class="rounded-btn text-lg custom-color">Accessories</a>
              </li>
              <li>
                <a class="rounded-btn text-lg custom-color">Marketing</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
      <div class="drawer-side">
        <label for="my-drawer-3" class="drawer-overlay"></label>
        <ul
          class="p-4 h-screen overflow-y-auto menu w-80 bg-base-100"
          style="
    position: fixed;
"
        >
          <li><a>CUPS</a></li>
          <li><a>SPOONS</a></li>
          <li><a>LIDS</a></li>
        </ul>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isMenuOpen: false,
      atTopOfPage: true,
    };
  },
  beforeMount() {
    window.addEventListener("scroll", this.handleScroll);
  },
  methods: {
    // the function to call when the user scrolls, added as a method
    handleScroll() {
      // when the user scrolls, check the pageYOffset
      if (window.pageYOffset > 0) {
        // user is scrolled
        if (this.view.atTopOfPage) this.view.atTopOfPage = false;
      } else {
        // user is at top of page
        if (!this.view.atTopOfPage) this.view.atTopOfPage = true;
      }
    },
  },
};
</script>
