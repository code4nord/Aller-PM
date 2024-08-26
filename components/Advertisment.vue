<template>
    <div v-if="show">
        <button @click="show = false" class="flex relative close-position text-white">X</button>
        <div class="relative h-full w-full">
        <div class="h-full w-full advertisment">
            <img src="https://cdn.pixabay.com/photo/2021/12/23/03/58/da-guojing-6888603_1280.jpg" class="h-full w-full" alt="Example Image" />
        </div>
        <div class="flex flex-col text-white text-sm text-left absolute top-0 btn-position">
        <span class="mb-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Velit, laborum.</span>
        <button class="bg-white text-black text-xs py-1 px-2 rounded w-24">SHOP HER</button>
        <div class="w-full flex justify-end mt-20">
            <div class="mb-3 font-mono font-semibold w-20">Kitchen Living Dinner</div>
        </div>
        </div>
        </div>
    </div>
</template>


<script>
export default {
 name: 'Advertisment',
 data() {
    return {
        show: true,
    }
 }
}
</script>

<style>
.advertisment {
  width: 335px;
  height: 245px;
}

.close-position {
  right: -325px;
  top: 4px;
  z-index: 10;
}

.btn-position {
  top: 15px;
  left: 25px;
}
</style>