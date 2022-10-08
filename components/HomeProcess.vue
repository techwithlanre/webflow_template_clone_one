<template>
  <section class="px-10">
    <div class="md:px-[300px] bg-white py-20 mt-10 tracking-wide">
      <div class="md:flex flex-row justify-between items-center md:space-x-[100px]">
        <div class="flex flex-col md:w-[700px] max-w-screen-md">
          <div class="flex flex-row gap-2">
            <div class="p-2 md:p-4 bg-[#f2a7d8] rounded-l-full"></div>
            <div class="p-2 md:p-4 bg-[#47bdff] rounded-tr-full"></div>
          </div>
          <h1 class="text-3xl md:text-5xl text-[#28264d] font-bold mt-5">A Simple, yet <br>effective five steps <br>process.</h1>
          <div class="hidden md:block md:h-[500px] md:w-[500px]">
            <img class="rounded-full mt-10" src="~assets/images/process.jpg" alt="">
          </div>
        </div>
        <div class="flex flex-col gap-8 mt-10">
          <div class="md:flex md:space-x-4">
            <div class="mb-10 flex flex-row gap-10 items-top bg-green-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-green-400 ">Project Idea</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>

            <div class="flex flex-row gap-10 items-top bg-yellow-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-yellow-400">Research</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>
          </div>

          <div class="flex space-x-4">
            <div class="flex flex-row gap-10 items-top bg-blue-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-blue-400">Execution</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>

            <div class="flex flex-row gap-10 items-top bg-orange-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-orange-400">Testing</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>
          </div>

          <div class="md:flex md:space-x-4">
            <div class="flex flex-row gap-10 items-center bg-purple-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-purple-400">Launch</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>
            <div class="flex flex-row gap-10 items-top bg-red-100 p-5 rounded-lg">
              <div class="max-w-xl">
                <h1 class="text-3xl font-bold text-red-400">Research</h1>
                <p class="mt-5 text-gray-700">Lorem ipsum dolor sit amet, consectetur adipiscing elit.  </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "HomeProcess"
    }
</script>

<style scoped>

</style>
