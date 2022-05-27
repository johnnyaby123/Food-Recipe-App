<template>

  <div>
    <div class="bg-white-100">
      <nav
        class="
          container
          px-6
          py-8
          mx-auto
          md:flex md:justify-between md:items-center
        "
      >
        <div class=" flex items-center justify-between">
          <div
            
            class="
              text-xl
              font-bold
              text-gray-400
              md:text-2xl
              font-Macondo
            "
            >JO
          </div>
          <div
            
            class="
              text-xl
              font-bold
              text-blue-100
              md:text-2xl
              font-Macondo
            "
            >JO
          </div>
          <!-- Mobile menu button -->
        </div>
        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <ul
          class="
            flex
            space-x-24
            mr-auto
            ml-80
          "
        >
          <li class="text-sm font-bold text-gray-800 hover:text-blue-100">
            <router-link to="/" href="#">Home</router-link>
          </li>
          
          <li class="text-sm font-bold text-gray-800 hover:text-blue-100">
            <router-link to="/recipes" href="#">Recipes</router-link>
          </li>
          <li class="text-sm font-bold text-gray-800 hover:text-blue-100">
            <router-link to="/about" href="#">About</router-link>
          </li>
          <li class="text-sm font-bold text-gray-800 hover:text-blue-100">
             <router-link to="/favorite" href="#">Favorite</router-link>
          </li>
        </ul>
        <div class="pt-2 relative mx-auto text-gray-600">
        <input class="border-2 border-gray-300 bg-white h-10 px-5 pr-16 rounded-full text-sm focus:outline-none"
          type="search" name="search" placeholder="Search">
        <button type="submit" class="absolute right-0 top-0 mt-5 mr-4">
          <svg class="text-gray-600 h-4 w-4 fill-current" xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px"
            viewBox="0 0 56.966 56.966" style="enable-background:new 0 0 56.966 56.966;" xml:space="preserve"
            width="512px" height="512px">
            <path
              d="M55.146,51.887L41.588,37.786c3.486-4.144,5.396-9.358,5.396-14.786c0-12.682-10.318-23-23-23s-23,10.318-23,23  s10.318,23,23,23c4.761,0,9.298-1.436,13.177-4.162l13.661,14.208c0.571,0.593,1.339,0.92,2.162,0.92  c0.779,0,1.518-0.297,2.079-0.837C56.255,54.982,56.293,53.08,55.146,51.887z M23.984,6c9.374,0,17,7.626,17,17s-7.626,17-17,17  s-17-7.626-17-17S14.61,6,23.984,6z" />
          </svg>
        </button>
      </div>
      
       <div>
         <button class="
         bg-blue-100
         ml-12
         
         px-4
         py-2
         text-white
         rounded-full
         font-Poppins
         ">
             <router-link to="/Signin" href="#">Sign in</router-link>
         </button>
     </div>
      </nav>
    </div>
    <div 
    class="
    h-screen
    w-full
    flex
    items-center
     ">
     <div class="flex-col" >
         <div class="
     ml-32
     -mt-40
     flex-col
     text-7xl
     font-serif">
        Let’s Start <br/>
        Cooking With <br/>
        Popular Recipes
     </div>
     <div class="
     font-Poppins
     text-sm
     ml-32
     mt-8">
         Want to learn cook but confused how to start? <br/> No need to worry again!
     </div>
     <div>
         <button class="
         bg-blue-100
         ml-32
         mt-8
         px-8
         py-2
         text-white
         rounded-full
         font-Poppins
         ">
             <router-link to="/Signup" href="#">Get started</router-link>
         </button>
     </div>
     </div>

     <div class="
     flex justify-center
     -mt-40
     ">
         <img src="../assets/food1.png"
         class="
         w-2/3"/>
     </div>   
    </div>
  </div>
</template>
<script>
export default {
  name: "Home",
  data() {
    return {
      showMenu: false,
    };
  },
};
</script>
