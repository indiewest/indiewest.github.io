<template>
    <div class="px-[24px] lg:px-[40px]">
        <div class="text-blue text-[90px] leading-none">
            THERE IS<br/>
            NO BETTER PARTNER.<br/>
            BECAUSE WE’RE HERE.
        </div>
        <ul class="grid grid-cols-1 gap-x-[40px] gap-y-[80px] mt-[44px]">
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
        <!-- <img src="~/assets/main-logo.svg" class="w-[80vw] lg:w-[600px]"/> -->
    </div>
</template>