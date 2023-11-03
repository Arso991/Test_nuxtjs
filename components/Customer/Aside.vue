<template>
    <div
        class="h-screen w-32 overflow-y-scroll space-y-10 scroll border border-slate-100 flex flex-col justify-between text-center text-xs font-semibold sticky bottom-0 left-0 top-0">
        <div class="mt-20">
            <MenuView />

            <MenuArchive />

            <MenuMsg />

            <MenuCreditCard />

            <MenuFile />

            <MenuPhone />
        </div>
        <div>

            <MenuSetting />

            <MenuPower />

        </div>
    </div>
</template>
<style>
.scroll::-webkit-scrollbar {
    width: 5px;
    border-radius: 10px;

}

.scroll::-webkit-scrollbar-track {
    -webkit-box-shadow: inset 0 0 6px rgba(0, 0, 0, 0.3)
}

.scroll::-webkit-scrollbar-thumb {
    background: #666;
    outline: 1px solid #eee;
}
</style>