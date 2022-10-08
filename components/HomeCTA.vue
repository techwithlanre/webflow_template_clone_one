<template>
    <section class="bg-[#28264d] px-10">
      <div class="py-10 md:px-[300px] md:py-[150px] md:flex justify-between items-end">
        <div class="w-[100%] md:w-[50%]">
          <div class="flex flex-row gap-2">
            <div class="p-2 md:p-4 bg-[#f2a7d8] rounded-l-full"></div>
            <div class="p-2 md:p-4 bg-[#47bdff] rounded-tr-full"></div>
          </div>
          <h1 class="text-3xl md:text-4xl text-white font-bold mt-5">Let's build something<br>great!</h1>
          <p class="text-gray-300 mt-5">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Suspendisse varius enim in eros elementum tristique. Duis cursus, mi quis viverra ornare, eros dolor interdum nulla, ut commodo diam libero vitae erat.</p>
        </div>
        <div class="flex gap-5 md:mt-0 mt-10">
          <button class="bg-[#47bdff] py-5 px-8 hover:px-6 hover:py-3 duration-500 hover:bg-blue-900 hover:text-gray-100 rounded-full font-semibold text-[#28264d]">HIRE US</button>
          <button class="bg-white py-5 px-8 rounded-full font-semibold text-[#28264d]">ABOUT US</button>
        </div>
      </div>
      <div class="hidden py-10 md:px-[300px] md:py-[10px] md:pb-[190px] md:flex flex-row gap-0 justify-center">
        <div class="h-[300px] w-[50%] md:h-[600px] md:w-full bg-[#eda0a8] rounded-tl-[75px] md:rounded-tl-[150px] md:rounded-br-[150px] rounded-br-[75px]"></div>
        <div class="h-[300px] w-[50%] md:h-[600px] md:w-full flex md:flex-col gap-0">
          <div class="h-[50%] w-[100%] bg-[#9bdaf2] rounded-full"></div>
          <div class="h-[50%] w-[100%] bg-[#e5ba08]"></div>
        </div>
        <div class="h-[600px] w-full flex flex-col gap-0">
          <div class="h-[50%] bg-[#94b4bf] rounded-br-[150px]"></div>
          <div class="h-[50%] bg-[#f25260] rounded-full"></div>
        </div>
        <div class="h-[600px] w-full flex flex-col gap-0">
          <div class="h-[50%] bg-[#fdc067] rounded-tl-[150px]"></div>
          <div class="h-[50%] bg-[#d74747] rounded-b-full"></div>
        </div>
      </div>
    </section>
</template>

<script>
    export default {
        name: "HomeCTA"
    }
</script>

<style scoped>

</style>
