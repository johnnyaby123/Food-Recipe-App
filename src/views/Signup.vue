<template>
  <div class="
  flex">
      <div class="
      
      h-screen
      w-3/5">
      <div>
          <h3 class="
          font-Poppins
          text-2xl
          flex items-center justify-center
          py-20
          tracking-widest">Create Account</h3>
          <div>
          <label class="flex ml-48 mt-4 font-Poppins">Name</label>
          <input
          class="border focus:outline-gray-400 w-1/2 py-2 px-6 ml-48 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder="Enter your name"/>
          </div>
          <div>
          <label class="flex ml-48 mt-4 font-Poppins">Email</label>
          <input
          class="border focus:outline-gray-400 w-1/2 py-2 px-6 ml-48 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder="example@website.com"/>
          </div>
          <div>
          <label class="flex ml-48 mt-4 font-Poppins">Password</label>
          <input
          class="border focus:outline-gray-400 w-1/2 py-2 px-6 ml-48 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="password"
          placeholder="Enter your password"/>
          </div>
          <div>
          <label class="flex ml-48 mt-4 font-Poppins">Confirm Password</label>
          <input
          class="border focus:outline-gray-400 w-1/2 py-2 px-6 ml-48 mt-4 leading-tight shadow rounded-3xl font-Poppins placeholder:font-Poppins appearance-none"
          type="text"
          placeholder="Confirm your password"/>
          </div>
          <div class="flex items-center justify-center mt-10">
              <button class="
              bg-blue-100
              text-white
              font-Poppins
              py-1
              w-1/4
              rounded-full
              ">
                  Sign up
              </button>
          </div>
      </div>

      </div>
    <div class="bg-blue-100 h-screen w-2/5">

    </div>
  </div>
</template>

<script>
export default {
        name: "Signup",
        setup(){
            
        }
    }
</script>

<style>
</style>