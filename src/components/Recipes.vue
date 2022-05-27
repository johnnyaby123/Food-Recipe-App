<template>
<div 
class="
bg-blue-300
h-screen
w-full
flex
">
<div class="
bg-white
h-screen
w-72
flex justify-center">
<div class="flex-col m-10 ">
    <div class="flex justify-center">
          <div class="
              text-xl
              font-bold
              text-gray-400
              md:text-4xl
              font-Macondo
            "
            >JO
          </div>
          <div class="
              text-xl
              font-bold
              text-blue-100
              md:text-4xl
              font-Macondo
            "
            >JO
          </div>
    </div>
          <router-link class=" font-Poppins flex justify-center mt-32 ">Overview</router-link>
          <router-link class=" font-Poppins flex justify-center mt-16 ">Recipes</router-link>
          <router-link class=" font-Poppins flex justify-center mt-16 ">Favorites</router-link>
          <router-link class=" font-Poppins flex justify-center mt-16 ">Setting</router-link>
          <div class="
              flex justify-center
              bg-blue-100
              w-56
              h-48
              mt-32
              rounded-xl">
              <button>
                  <div class="
                  flex items-center justify-center
                  text-white
                  mt-16">Share your own Recipe <br/> with the community</div>

                  <button class="
                  bg-white
                  w-48
                  h-10
                  mt-6
                  rounded-3xl">
                  <div class="
                  text-blue-100">
                      Upload Now
                  </div>
                  </button>
              </button>
          </div>
</div>
</div>

<div class="
font-Poppins
 ml-12 
 w-full
 text-gray-600
 ">
<div class="
font-Poppins
 ml-12 
 w-full
 text-gray-600
 flex
 ">
        <input class=" border-none bg-white mt-8 h-10 w-2/3 px-8  rounded-full text-sm focus:outline-none"
          type="search" name="search" placeholder="Search">
        <button type="submit" class="">
          <svg class="text-gray-600 h-4 w-4 fill-current" xmlns="http://www.w3.org/2000/svg"
            xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1" id="Capa_1" x="0px" y="0px"
            viewBox="0 0 56.966 56.966" style="enable-background:new 0 0 56.966 56.966;" xml:space="preserve"
            width="512px" height="512px">
          </svg>
        </button>
        <div class="
        mt-8
        flex justify-center items-center
        h-10
        w-32
        bg-white
        rounded-full">
        filter
        </div>
        <div class="flex -space-x-1 overflow-hidden">
        <img class="inline-block h-10 w-10 rounded-full mt-8 ml-36 ring-2 ring-white" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="" />
        </div>
</div>
<div class="">
<div class="
font-Poppins
ml-12
text-2xl
mt-16
">
    Your Recipes
</div>
<div class=" flex space-x-4 justify-around mt-8">
<div class="w-1/3 h-1/2 bg-white">
<div class="flex">
<img src="../assets/food3.png" class="
w-1/2 mt-10 ml-10"/>
<div class="m-10">
<div class="text-2xl font-Poppins">Food 1</div>
<div>103 kcal</div>
</div>
</div>
<p class="flex m-12 mb-8 font-Poppins text-xl">Ingredient</p>
<div class="flex justify-around">
<div class=" flex justify-around grid gap-4 grid-cols-3 grid-rows-3">
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
</div>
</div>
<router-link class="
text-blue-100
flex
ml-10
mb-4" >Readmore ...</router-link>

</div>
<div class="w-1/3 h-1/2 bg-white">
<div class="flex">
<img src="../assets/food3.png" class="
w-1/2 mt-10 ml-10"/>
<div class="m-10">
<div class="text-2xl font-Poppins">Food 1</div>
<div>103 kcal</div>
</div>
</div>
<p class="flex m-12 mb-8 font-Poppins text-xl">Ingredient</p>
<div class="flex justify-around">
<div class=" flex justify-around grid gap-4 grid-cols-3 grid-rows-3">
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
</div>
</div>
<router-link class="
text-blue-100
flex
ml-10
mb-4" >Readmore ...</router-link>

</div>
<div class="w-1/3 h-1/2 bg-white">
<div class="flex">
<img src="../assets/food3.png" class="
w-1/2 mt-10 ml-10"/>
<div class="m-10">
<div class="text-2xl font-Poppins">Food 1</div>
<div>103 kcal</div>
</div>
</div>
<p class="flex m-12 mb-8 font-Poppins text-xl">Ingredient</p>
<div class="flex justify-around">
<div class=" flex justify-around grid gap-4 grid-cols-3 grid-rows-3">
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
<div class="
bg-blue-100
w-24
h-10 
p-2
text-sm"> Ingredient 1
</div>
</div>
</div>
<router-link class="
text-blue-100
flex
ml-10
mb-4" >Readmore ...</router-link>

</div>

</div>
</div>
</div>
</div>
</template>