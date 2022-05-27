import { ArrowLeftIcon } from "@vue-hero-icons/outline"
<template>
    <div class="bg-blue-300 w-full h-screen fixed">
    <div class="flex">
    <div class="flex mt-8 ml-28">
          <div class="
              text-xl
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

    <router-link class=" w-full flex justify-end mr-12 -space-x-1 overflow-hidden ">
    <img class="inline-block h-10 w-10 rounded-full mt-8 ml-36 ring-2 ring-white" src="https://images.unsplash.com/photo-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80" alt="" />
    </router-link>

    </div>
    
    <div class="flex  justify-center  w-full h-screen" >
    <div class=" flex  mt-10 w-3/4 h-3/4 bg-white">
    <div class="flex flex-col">
    <div class="flex flex-row">
    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 m-8" viewBox="0 0 20 20" fill="currentColor">
    <path fill-rule="evenodd" d="M9.707 16.707a1 1 0 01-1.414 0l-6-6a1 1 0 010-1.414l6-6a1 1 0 011.414 1.414L5.414 9H17a1 1 0 110 2H5.414l4.293 4.293a1 1 0 010 1.414z" clip-rule="evenodd" />
    </svg> 
    <div class=" flex mt-6 ml-10 font-Poppins text-3xl">Upload </div>
    </div> 
    
    <div class="flex flex-row">

    <div class="flex flex-col">
    <div class="">
        <div class="ml-24 mt-8">Title</div>
        <div>
             <input
          class="border focus:outline-gray-400 w-3/4 py-2 px-6 ml-24 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder=""/>
        </div>
    </div>

    <div class="">
        <div class="ml-24 mt-8">Description</div>
        <div>
             <input
          class="border focus:outline-gray-400 w-3/4 h-24 py-2 px-6 ml-24 mt-4 leading-tight shadow rounded-lg font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder=""/>
        </div>
    </div>

    <div class="">
        <div class="ml-24 mt-8">Category</div>
        <div>
             <input
          class="border focus:outline-gray-400 w-3/4 py-2 px-6 ml-24 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder=""/>
        </div>
    </div>

    <div class="">
        <div class="ml-24 mt-8">Set time in minute</div>
        <div>
             <input
          class="border focus:outline-gray-400 w-3/4 py-2 px-6 ml-24 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder=""/>
        </div>
    </div>

    </div>
    <div class="flex flex-col">
        <div class="mt-8 ml-64">
            Ingredient
        </div>
        <div class="mt-2 ml-64">
            <svg xmlns="http://www.w3.org/2000/svg" class="h-12 w-12 " viewBox="0 0 20 20" fill="#57DAF6">
            <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm1-11a1 1 0 10-2 0v2H7a1 1 0 100 2h2v2a1 1 0 102 0v-2h2a1 1 0 100-2h-2V7z" clip-rule="evenodd" />
            </svg>
        </div>
        <div class="ml-40">
        <div class="ml-24 mt-8">Steps</div>
        <div>
             <input
          class="border focus:outline-gray-400 w-96 h-48 py-2 px-6 ml-24 mt-4 leading-tight shadow rounded-lg font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder=""/>
        </div>
         </div>
          <div class="ml-40">
        <div class="ml-24 mt-8">Uplaod image for thumbnail</div>
        <div>
             <button class="h-10 w-40 bg-blue-100 ml-24 mt-4 rounded-full text-white"> Browse</button>
        </div>
    </div>
        
    </div>
    </div>
    
    </div>
    </div>
    </div>  
    </div>
</template>


<script>
export default {
    name: "upload",
}
</script>