<script setup>

</script>

<template>
  <div class="bg-gradient-to-br min-h-screen from-emerald-950 to-indigo-950 text-teal-100 p-6">
     <h1 class="flex items-center justify-center  text-6xl my-6">
      Pozdrav, ja sam <span class="text-cyan-400"> Elen Hajdarović</span>
     </h1>
     <hr class="w-[1024px] opacity-75 border-2 rounded-full mx-auto my-8"/>
     <h2 class="text-2xl text-teal-100/75  pl-58 ">Moji omiljeni filmovi:</h2>
     <div class="justify-center gap-10 my-6">
        <div class="flex gap-6 justify-center">
        <div class="w-[320px] h-[480px] bg-gray-300 rounded-md flex items-center justify-center  text-6xl ">
         <img src="/anon.jpg" class="h-full w-full"/>
        </div>
        <div class="w-[320px] h-[480px] bg-gray-300 rounded-md flex items-center justify-center text-6xl ">
          <img src="/spy_next_door.jpg" class="w-full h-full" />
        </div>
        <div class="w-[320px] h-[480px] bg-gray-300 rounded-md flex items-center justify-centertext-6xl ">
          <img src="/titanic.jpg" class="h-full w-full"/>
        </div>
      </div>
      <div class="flex  justify-center text-2xl my-4  ">
        <p class="ml-auto">Anon</p>
        <p class="mx-auto">Spy Next Door</p>
        <p class="mr-auto">Titanic</p>
      </div>
     </div>
  </div>

</template>

<style scoped>

</style>
