<template>
    <form action="" class="w-2/3 px-3">
        <div class="grid gap-5 grid-cols-2 grid-rows-2">
            <div class="flex flex-col">
                <label class="text-xs" for="">Nom</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text"
                    placeholder="Inserer votre nom">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Prénom</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text"
                    placeholder="Inserer votre nom">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Téléphone</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text"
                    placeholder="Votre téléphone">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">E-mail</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text"
                    placeholder="Inserer votre Email">
            </div>
        </div>
        <div class="flex flex-col my-4">
            <label class="text-xs" for="">Nom du projet</label>
            <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text"
                placeholder="Inserer votre Email">
        </div>
        <div class="grid grid-cols-2">
            <div class="flex flex-col">
                <label class="text-xs" for="">Pays</label>
                <select
                    class="text-xs text-slate-400 bg-transparent border border-slate-300 p-1 rounded-lg mt-2 outline-none"
                    name="" id="">
                    <option value="" selected>Sélectionnez le pays</option>
                </select>
            </div>
        </div>
    </form>
</template>