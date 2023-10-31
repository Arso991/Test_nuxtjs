<template>
    <table class="w-full ps-8 table-auto">
        <thead>
            <tr class="text-slate-300 font-semibold">
                <td class="ps-5 py-4">Nom</td>
                <td>Email</td>
                <td>Numéro</td>
                <td>Pays</td>
                <td class="ps-e">Projet</td>
            </tr>
        </thead>
        <tbody>
            <tr class="py-2 border-b" v-for="element in clientTab">
                <td class="ps-5 py-2">{{ element.name }}</td>
                <td>{{ element.email }}</td>
                <td>{{ element.numéro }}</td>
                <td>icon</td>
                <td>{{ element.projet }}</td>
                <td class="pe-5">***</td>
            </tr>
        </tbody>
    </table>
</template>
<script setup>
const clientTab = [
    {
        name: "Florence Kwame",
        email: "florencek@gmail.com",
        numéro: "00229 97 45 09 23",
        projet:1
    },
    {
        name: "Emile Zinsou",
        email: "zinsouek@gmail.com",
        numéro: "00229 97 45 09 23",
        projet:2
    },
    {
        name: "Florence Kwame",
        email: "florencek@gmail.com",
        numéro: "00229 97 45 09 23",
        projet:1
    },
    {
        name: "Florence Kwame",
        email: "florencek@gmail.com",
        numéro: "00229 97 45 09 23",
        projet:4
    }
]
</script>