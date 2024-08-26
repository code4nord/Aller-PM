<template>
    <div class="">
      <main class="flex mt-20 mx-6">
        <div class="container mx-auto grid grid-cols-1 md:grid-cols-2 xl:grid-cols-3 xl:gap-4 gap-y-4">
            <!-- Main Story -->
          <div class="xl:col-span-1 md:col-span-3 sm:col-span-1 bg-white pb-4 rounded shadow-md">
            <div class="">
              <img 
              src="https://cdn.pixabay.com/photo/2022/11/27/10/31/bird-7619338_1280.jpg" 
              alt="Main Story Image" 
              class="mb-4 w-full h-full rounded"
            />
            </div>
            <div class="text-xs text-red-600 font-bold uppercase mb-2 text-center">En læser fortæller</div>
            <h2 class="font-bold text-lg text-center">Jeg higede efter omsorg - del 2:5</h2>
          </div>
          <!-- Additional Stories -->
          <div class="xl:col-span-2 md:col-span-2 grid grid-cols-1 md:grid-cols-2 md:gap-x-4 gap-4">
            <div class="bg-white pb-4 rounded shadow-md">
              <div class="class mb-4">
                <img 
                src="https://cdn.pixabay.com/photo/2015/07/31/15/01/girl-869213_1280.jpg" 
                alt="Story Image" 
                class="mb-4 w-full h-full rounded"
              />
              </div>
              <div class="text-xs text-red-600 text-center font-bold uppercase mb-2">Når livet gør ondt</div>
              <h3 class="font-bold text-base text-center">33-årige Dagmar har måske kun få måneder tilbage</h3>
            </div>

            <div class="bg-white pb-4 rounded shadow-md">
              <div class="class mb-4">
                <img 
                src="https://cdn.pixabay.com/photo/2022/08/21/21/24/colours-7402147_1280.jpg" 
                alt="Story Image" 
                class="mb-4 w-full h-full rounded"
              />
              </div>
              <div class="text-xs text-red-600 font-bold uppercase mb-2 text-center">Når livet gør ondt</div>
              <h3 class="font-bold text-base text-center">Stinne og Christian er uhelbredeligt syge med kræft</h3>
            </div>
          </div>
        </div>

        <!-- Advertisement -->
        <advertisment class="fixed lg:hidden flex adv-position" />
        <advertisment class="hidden lg:flex ml-6 justify-start" />
      </main>
    </div>
</template>

<script>
import Advertisment from './Advertisment.vue';

export default {
 name: 'MainContainer',
 components: {
    Advertisment,
 },
 data() {
    return {
        show: true,
    }
 }
}
</script>

<style scoped>
.content-height {
    height: 130vh;
}
.adv-position {
  bottom: 25px;
  right: 25px;;
}
</style>