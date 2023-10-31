<template>
    <form action="" class="w-2/3 px-3">
        <div class="grid gap-5 grid-cols-2 grid-rows-3">
            <div class="flex flex-col">
                <label class="text-xs" for="">Nom</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text" placeholder="inserer le nom du client">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Prénom</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text" placeholder="inserer le prénom du client">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Téléphone</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text" placeholder="inserer le numéro de téléphone">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">E-mail</label>
                <input class="text-xs border border-slate-300 p-1 rounded-lg mt-2 outline-none" type="text" placeholder="inserer l'adresse e-mail du client">
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Pays du projet</label>
                <select class="text-xs text-slate-400 bg-transparent border border-slate-300 p-1 rounded-lg mt-2 outline-none" name="" id="">
                    <option value="" selected>Sélectionnez le pays</option>
                </select>
            </div>
            <div class="flex flex-col">
                <label class="text-xs" for="">Type de client</label>
                <select class="text-xs text-slate-400 bg-transparent border border-slate-300 p-1 rounded-lg mt-2 outline-none" name="" id="">
                    <option value="" selected>Selectionnez le type de client</option>
                </select>
            </div>

        </div>
        <button class="mt-10 px-10 py-2 bg-[#3d4553] rounded-xl text-[#908253]" type="submit">AJOUTER</button>
    </form>
</template>