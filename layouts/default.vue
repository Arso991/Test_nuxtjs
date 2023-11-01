<template>
    <div class="flex">
        <AsideBar/>
        <div class="bg-stone-50 w-full">
            <header class="h-12 bg-white sticky left-0 top-0 right-0 flex items-center justify-end">
                <div class="me-3">
                    <AddClientBtn />
                </div>
                <div class="flex gap-2 ps-5 pe-4 border-s-2 border-black">
                    <div class="h-6 w-6 bg-slate-300 rounded-full">
                    </div>
                    <div>
                        <small>Admin <span><Icon name="ic-baseline-keyboard-arrow-down" /></span> </small>
                    </div>
                </div>
            </header>

            <div class="container mx-auto ps-20 pe-20 py-16">
                <slot />
            </div>
        </div>
    </div>
</template>