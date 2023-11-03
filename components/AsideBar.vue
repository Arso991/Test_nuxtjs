<template>
    <div class="w-32 flex justify-center sticky top-0 left-0 bottom-0 h-screen">
        <div class="text-center w-full overflow-y-scroll scroll space-y-10">
            <h1 class="mt-10 text-2xl">ilé.éé</h1>
            <div>
                <NuxtLink to="/">
                    <MenuView />
                </NuxtLink>
                <NuxtLink to="/projects/1">
                    <MenuStore />
                </NuxtLink>
                <NuxtLink to="">
                    <MenuLayers />
                </NuxtLink>
                <NuxtLink to="">
                    <MenuArchive />
                </NuxtLink>
                <NuxtLink to="">
                    <MenuMsg /> 
                </NuxtLink>
                <NuxtLink to="">
                    <MenuCreditCard />
                </NuxtLink>
                <NuxtLink to="/clients">
                    <MenuAccount />
                </NuxtLink>
                <NuxtLink to="">
                    <MenuPhone />
                </NuxtLink>
            </div>
            <div>
                <NuxtLink to="">
                    <MenuSetting />
                </NuxtLink>
                <NuxtLink to="">
                    <MenuPower />
                </NuxtLink>
            </div>
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