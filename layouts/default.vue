<template>
    <div class="wrap min-h-dvh flex flex-col justify-between">
        <div class="flex flex-col grow">
            <AppHeader />
            <div class="flex-col grow flex">
                <NuxtPage />
            </div>
        </div>
        <AppFooter />
    </div>
</template>

<style>
    html, body {
        -ms-overflow-style: none; /* IE and Edge */
        scrollbar-width: none; /* Firefox */
    }
    html::-webkit-scrollbar, body::-webkit-scrollbar {
        display: none; /* Chrome, Safari, Opera*/
    }
</style>