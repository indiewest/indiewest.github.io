<template>
    <div class="px-[24px] lg:px-[40px] pt-[60px] pb-[140px]">
        <div class="mb-[88px] text-md lg:text-2xl text-blue leading-normal">
            <ul class="flex gap-[20px] underline opacity-100">
                <li><NuxtLink>ALL</NuxtLink></li>
            </ul>
            <ul class="flex gap-[20px] opacity-50">
                <li>BRANDING</li><li>CONTENTS</li><li>ILLUSTRATION</li><li>EXHIBITION</li>
            </ul>
            <ul class="flex gap-[20px] opacity-50">
                <li>PACKAGE</li><li>PRODUCT</li><li>CHARACTER</li><li>UXUI</li>
            </ul>
        </div>
        <ul class="grid grid-cols-1 md:grid-cols-2 gap-x-[40px] gap-y-[80px]">
            <li class="work-item">
                <NuxtLink to="/workDetail/project-mkop">
                    <div class="w-full overflow-hidden">
                        <img src="~/assets/work/mkop/MKOP_WEB-01.jpg" class="w-full transition">
                    </div>
                    <h3 class="text-blue pt lg:text-[36px] text-[24px] mt-[24px] leading-tight">MAKE.O.PEACE BRAND DESIGN</h3>
                    <h5 class="text-blue text-sm lg:text-lg">2022 · BRANDING · PACKAGE</h5>
                </NuxtLink>
            </li>
            <li class="work-item">
                <NuxtLink to="/workDetail/project-uf">
                    <div class="w-full overflow-hidden">
                        <img src="~/assets/work/uf/UF_WEB-01.jpg" class="w-full transition">
                    </div>
                    <h3 class="text-blue pt lg:text-[36px] text-[24px] mt-[24px] leading-tight">UNE FEMME BRAND DESIGN</h3>
                    <h5 class="text-blue text-sm lg:text-lg">2020 · BRANDING · PACKAGE</h5>
                </NuxtLink>
            </li>
        </ul>
    </div>
</template>

<style>
    .work-item:hover h3 {
        text-decoration: underline;
    }
    .work-item:hover img {
        transform: scale(1.05);
    }
</style>