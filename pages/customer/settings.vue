<template>
    <div class="p-8">
        <h1 class="font-medium">Paramètres de votre espace</h1>
        <button class="my-10 px-10 py-2 bg-[#3d4553] rounded-md text-white">Informations perso</button>
        <CustomerSettingForm />
    </div>
</template>
<script setup>
definePageMeta({
    layout: "customer"
})
</script>