<template>
  <section class="px-10 bg-gray-100 mt-20">
    <div class="md:px-[300px] py-20 mt-10 tracking-wide">
      <div class="md:flex flex-row justify-between items-center md:space-x-[100px]">
        <div class="flex flex-col md:w-[700px] max-w-screen-md">
          <div class="flex flex-row gap-2">
            <div class="p-2 md:p-4 bg-[#f2a7d8] rounded-l-full"></div>
            <div class="p-2 md:p-4 bg-[#47bdff] rounded-tr-full"></div>
          </div>
          <h1 class="text-3xl md:text-5xl text-[#28264d] font-bold mt-5">See our latest <br>projects</h1>
        </div>
      </div>
      <div class="md:flex flex-row gap-12 mt-10">
        <div class="w-[100%] mb-20 flex flex-col md:w-[33%] md:mb-0">
          <img class="rounded-tl-[200px] hover:rounded-tl-[150px] duration-700 " src="https://uploads-ssl.webflow.com/628656d58480f6b4a1473485/62aa636903627dea288a0aed_thumb-web-design.jpg" alt="">
          <div class="flex justify-between mt-5">
            <p class="text-red-700">Royalfy</p>
            <p class="text-gray-500">June 15, 2022</p>
          </div>
          <div class="mt-5">
            <h1 class="font-bold text-2xl text-[#28264d] hover:text-blue-400 duration-500 cursor-pointer">Website Design Royalfy</h1>
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit lobortis arcu enim urna adipiscing praesent velit viverra sit semper lorem eu cursus vel hendrerit elementum</p>
          </div>
        </div>
        <div class="w-[100%] mb-20 flex flex-col md:w-[33%] md:mb-0 md:mt-[-100px]">
          <img src="https://uploads-ssl.webflow.com/628656d58480f6b4a1473485/62ab26d9e473140e22ce0f5b_thumb-brand-identity.jpg" class="rounded-b-[200px] hover:rounded-tl-[150px] duration-700" alt="">
          <div class="flex justify-between mt-5">
            <p class="text-red-700">Royalfy</p>
            <p class="text-gray-500">June 15, 2022</p>
          </div>
          <div class="mt-5">
            <h1 class="font-bold text-2xl text-[#28264d] hover:text-blue-400 duration-500 cursor-pointer">Website Design Royalfy</h1>
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit lobortis arcu enim urna adipiscing praesent velit viverra sit semper lorem eu cursus vel hendrerit elementum</p>
          </div>
        </div>
        <div class="w-[100%] flex flex-col md:w-[33%] md:mb-0 md:mt-[-200px]">
          <img  src="https://uploads-ssl.webflow.com/628656d58480f6b4a1473485/62ab7caa32e05699bef8c06c_thumb-packaging-design.jpg" class="rounded-tl-[200px] hover:rounded-tl-[150px] duration-700" alt="">
          <div class="flex justify-between mt-5">
            <p class="text-red-700">Royalfy</p>
            <p class="text-gray-500">June 15, 2022</p>
          </div>
          <div class="mt-5">
            <h1 class="font-bold text-2xl text-[#28264d] hover:text-blue-400 duration-500 cursor-pointer">Website Design Royalfy</h1>
            <p class="mt-2 text-gray-500">Lorem ipsum dolor sit amet, consectetur adipiscing elit lobortis arcu enim urna adipiscing praesent velit viverra sit semper lorem eu cursus vel hendrerit elementum</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
    export default {
        name: "HomePortfolio"
    }
</script>

<style scoped>

</style>
