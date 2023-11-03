<template>
    <div class="w-[37.4rem]">
        <table class="w-full table-auto bg-white rounded-lg border border-teal-100 w-96">
            <tbody>
                <tr>
                    <td class="border py-1 px-2 border-teal-100"> <small>Info</small></td>
                    <td class="border py-1 px-2 border-teal-100"> <small>Date</small></td>
                    <td class="border text-center py-1 px-2 border-teal-100"> <small>Chargé par</small></td>
                    <td class="border text-center py-1 px-2 border-teal-100"> <small>Action</small></td>
                </tr>
                <tr v-for="element in RapportTab">
                    <td class="border py-1 px-2 border-teal-100"> <small>{{element.info}}...</small></td>
                    <td class="border py-1 px-2 border-teal-100"> <small>{{element.date}}</small></td>
                    <td class="border text-center py-1 px-2 border-teal-100"> <small>{{element.name}}</small></td>
                    <td class="border text-center font-semibold py-1 px-2 border-teal-100"> <small>***</small></td>
                </tr>
            </tbody>
        </table>
    </div>
</template>
<script setup>
const RapportTab = [
    {
        info:"Recu paiement",
        date:"15/09/2023",
        name:"Admin",
    },
    {
        info:"Chargement fichier",
        date:"15/09/2023",
        name:"Marcel H.",
    },
    {
        info:"Recu paiement",
        date:"15/09/2023",
        name:"Admin",
    },
    {
        info:"Document propriété",
        date:"15/09/2023",
        name:"Kwame L.",
    },
    {
        info:"Carte Identité",
        date:"15/09/2023",
        name:"Kwame L.",
    },
    {
        info:"Carte Identité",
        date:"15/09/2023",
        name:"Kwame L.",
    },
    {
        info:"Carte Identité",
        date:"15/09/2023",
        name:"Kwame L.",
    },
    {
        info:"Carte Identité",
        date:"15/09/2023",
        name:"Kwame L.",
    },
    {
        info:"Carte Identité",
        date:"15/09/2023",
        name:"Kwame L.",
    }
]
</script>