<template>
    <div class="p-2 border w-[50rem] border-slate-100 rounded-lg mb-5">
        <div class="h-[20rem] w-full overflow-hidden mb-4">
            <img class="w-[100%] h-[100%] object-cover rounded-md" src="/6.jpg" alt="">
        </div>
        <div class="mb-8 flex items-center gap-10">
            <h2 class="font-medium">Duplex Erevan-Cotonou, Benin</h2>
            <h2 class="flex items-center gap-2 text-slate-800"><span>3 Chambres</span>
                <div class="w-3 h-3 bg-slate-100 rounded-full"></div><span>2 Bains</span>
                <div class="w-3 h-3 bg-slate-100 rounded-full"></div><span>1 Salon</span>
                <div class="w-3 h-3 bg-slate-100 rounded-full"></div><span>1 Cuisine</span>
            </h2>
        </div>
        <div class="flex gap-2">
            <div class="w-[6rem] h-[8rem]" v-for="element in images">
                <img class="w-[100%] h-[100%] object-cover rounded" :src="element" alt="">
            </div>
        </div>
    </div>
</template>
<script setup>
const images = ["/7.jpg", "/8.jpg", "/9.jpg", "/10.jpg", "/11.jpg", "/12.jpg", "/13.jpg", "/14.jpg", "/15.jpg",]
</script>