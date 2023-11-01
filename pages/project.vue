<template>
    <div class="flex gap-10">
        <div class="w-2/3 py-4 ps-4 pe-8 bg-white rounded-lg border border-teal-100">
            <h1 class="text-2xl font-semibold mb-8">Detail projet</h1>
            <div class="flex gap-2">
                <div class="flex flex-col gap-2">
                    <div class="w-48">
                        <img class="w-[100%] h-[100%] rounded-lg" src="/1.jpg" alt="">
                    </div>
                    <div class="w-48">
                        <img class="w-[100%] h-[100%] rounded-lg" src="/2.jpg" alt="">
                    </div>
                    <div class="w-48">
                        <img class="w-[100%] h-[100%] rounded-lg" src="/3.jpg" alt="">
                    </div>
                </div>
                <div class="overflow-hidden object-cover">
                    <img class="w-[100%] h-[100%] rounded-lg" src="/4.jpg" alt="">
                </div>
            </div>
            <div class="mt-4 flex justify-between items-center">
                <p class="font-semibold"> <span class="text-2xl"> <Icon name="ic-outline-house"/> </span> Duplex Erevan</p>
                <p class="text-xs flex gap-5"><span>3 chambres</span><span>2 Douches</span><span>1 Cuisine</span></p>
                <p class="font-semibold">150.000 $USD</p>
            </div>
            <small class="flex items-center gap-2 mt-4 mb-4"><span>Diaspora City</span>
                <div class="h-2 w-2 rounded-full bg-slate-300"></div><span>Wakanda</span>
            </small>
            <div class="pt-4 pb-8 border-t border-slate-300">
                <h1 class="text-xl font-semibold mb-2">Description</h1>
                <p class="text-xs">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptatem iure modi, quas sed
                    ipsa
                    expedita. Saepe,
                    quam distinctio? Aliquam nihil beatae autem, cupiditate minima illo maxime? Animi voluptate ullam hic!
                    Lorem
                    ipsum dolor sit amet consectetur adipisicing elit. Amet obcaecati mollitia quam enim quibusdam ratione
                    sunt
                    consequatur quis, hic modi magni vero, laudantium eveniet eligendi expedita quia eum, iure minus?</p>
            </div>
        </div>
        <div class="flex flex-col gap-5">
            <div class="bg-white p-4 flex flex-col justify-center border border-teal-100 rounded-lg">
                <div class="w-full flex justify-center">
                    <div class="overflow-hidden object-cover w-16 h-16 rounded-full mb-5">
                        <img class="w-[100%] h-[100%]" src="/5.jpg" alt="">
                    </div>
                </div>

                <small class="flex items-center justify-center gap-2 mb-4 font-semibold"><span>Marcel Houedo</span>
                    <div class="h-2 w-2 rounded-full bg-slate-300"></div><span class="text-teal-100">1 projet en
                        cours</span>
                </small>
                <p class="font-semibold mb-4 text-center text-sm">00229 97 23 34 90</p>
                <div class="border-t border-slate-300 text-center pt-4">
                    <button class="p-2 bg-teal-100 text-xs rounded-lg text-teal-400">Envoyez message <Icon name="mdi-pencil-box-outline" /> </button>
                </div>
            </div>
            <div class="bg-white p-5 border border-teal-100 rounded-lg">
                <h1 class="text-2xl text-center font-medium mb-8">Paiement</h1>
                <div class="flex items-center ps-8">
                    <div class="w-5 h-5 rounded-full flex items-center justify-center bg-teal-100"><Icon class="text-white text-xl" name="mdi-check" /></div>
                    <div class="w-14 h-1 bg-slate-100"></div>
                    <div class="w-4 h-4 rounded-full bg-slate-100"></div>
                    <div class="w-12 h-1 bg-slate-100"></div>
                    <div class="w-4 h-4 rounded-full bg-slate-100"></div>
                    <div class="w-12 h-1 bg-slate-100"></div>
                    <div class="w-4 h-4 rounded-full bg-slate-100"></div>
                    <div class="w-12 h-1 bg-slate-100"></div>
                    <div class="w-4 h-4 rounded-full bg-slate-100"></div>
                </div>
                <p class="text-left text-xs mt-2 mb-8">Frais dépôt transfert</p>
            </div>
            <div class="bg-white p-5 border border-teal-100 rounded-lg mt-5">
                <h1 class="text-2xl text-center font-medium mb-8">Avancement</h1>
                <div class="flex justify-center">
                    <PieChartjs />
                </div>
            </div>
        </div>
    </div>
</template>