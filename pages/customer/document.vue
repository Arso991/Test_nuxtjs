<template>
    <div class="p-8">
        <h1 class="text-xl font-medium mb-10">Document</h1>
        <div class="flex flex-wrap gap-10">
            <div class="p-5 w-[18rem] h-[9rem] border-2 border-slate-100 rounded-md leading-10">
                <div>
                    <Icon class="text-2xl" name="mdi-archive-outline" />
                </div>
                <h1 class="text-xl font-medium">Document Personnel</h1>
                <small class="text-slate-300">4 éléments</small>
            </div>
            <div class="p-5 w-[18rem] h-[9rem] border-2 border-slate-100 rounded-md leading-8">
                <div>
                    <Icon class="text-2xl" name="mdi-archive-outline" />
                </div>
                <h1 class="text-xl font-medium">Contrat</h1>
                <small class="text-slate-300">4 documents</small>
            </div>
            <div class="p-5 w-[18rem] h-[9rem] border-2 border-slate-100 rounded-md leading-8">
                <div>
                    <Icon class="text-2xl" name="mdi-archive-outline" />
                </div>
                <h1 class="text-xl font-medium">Suivi Notaire</h1>
                <small class="text-slate-300">3 documents</small>
            </div>
            <div class="p-5 w-[18rem] h-[9rem] border-2 border-slate-100 rounded-md leading-8">
                <div>
                    <Icon class="text-2xl" name="mdi-archive-outline" />
                </div>
                <h1 class="text-xl font-medium">Photos</h1>
                <small class="text-slate-300">4 documents</small>
            </div>
            <div class="p-5 w-[18rem] h-[9rem] border-2 border-slate-100 rounded-md leading-8">
                <div>
                    <Icon class="text-2xl" name="mdi-archive-outline" />
                </div>
                <h1 class="text-xl font-medium">Plans Projet</h1>
                <small class="text-slate-300">4 documents</small>
            </div>
        </div>
    </div>
</template>
<script setup>
definePageMeta({
    layout: "customer"
})
</script>