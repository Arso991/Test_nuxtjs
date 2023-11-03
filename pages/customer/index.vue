<template>
    <div class="py-8">
        <div class="px-8">
            <h1 class="text-xl font-semibold mb-5">Propriété</h1>
            <CustomerHouse />
        </div>

        <div class="pt-10 border-t-2 border-slate-100 px-8 mb-20">
            <h1 class="text-xl font-semibold mb-10">Rapports</h1>
            <div class="flex justify-between w-[50rem]">
                <CustomerReport-docs />
                <CustomerReport-notaire />
                <CustomerReport-payment />
            </div>
        </div>
    </div>
</template>
<script setup>
definePageMeta({
    layout: "customer"
})
</script>