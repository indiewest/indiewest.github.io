<template>
    <div class="px-[16px] sm:px-[24px] lg:px-[40px]">
        <div class="text-blue text-[30px] sm:text-[40px] md:text-[60px] xl:text-[90px] leading-[36px] sm:leading-[44px] md:leading-[64px] xl:leading-[96px] mt-[44px] sm:mt-[54px] xl:mt-[80px]">
            DESIGN PRODUCTION<br/>
            <div class="line-container inline-block w-[150px] sm:w-[190px] md:w-[300px] h-[24px] sm:h-[34px] md:h-[44px] xl:h-[66px] xl:w-[460px] mr-[6px] md:mr-[12px]">
                <div class="line" ></div>
            </div>INDIEWEST.<br/>
            WE OFFER CREATIVE SOLUTIONS.
        </div>
        <ul class="grid grid-cols-1 gap-y-[60px] md:gap-y-[120px] mt-[54px] sm:mt-[84px] mb-[44px] sm:mb-[64px] xl:mt-[124px] xl:mb-[124px]">
            <li class="work-item">
                <NuxtLink to="/workDetail/project-uf">
                    <div class="md:flex justify-between items-start">
                        <h2 class="text-blue pt text-[26px] sm:text-[34px] xl:text-[50px] leading-tight md:w-[40%]">UNE FEMME NEW YORK BRANDING</h2>
                        <div class="text-blue text-xs sm:text-sm xl:text-lg md:w-[50%] mt-[6px] md:mt-0 leading-normal">
                            Brand Strategy & package design project for UNE FEMME NEW YORK, which is woman's fashion brand based in New York.
                            <span class="hover:underline hidden sm:inline">
                                <br><br>
                                &#8594; Learn More
                            </span>
                        </div>
                    </div>
                    <div class="w-full overflow-hidden mt-[14px] xl:mt-[44px]">
                        <img src="/img/work/uf/UF_WEB-01.jpg" class="w-full transition">
                    </div>
                </NuxtLink>
            </li>
            <li class="work-item">
                <NuxtLink to="/workDetail/project-mkop">
                    <div class="md:flex justify-between items-start">
                        <h2 class="text-blue pt text-[26px] sm:text-[34px] xl:text-[50px] leading-tight md:w-[40%]">MAKE.O.PEACE BRANDING</h2>
                        <div class="text-blue text-xs sm:text-sm xl:text-lg md:w-[50%] mt-[6px] md:mt-0 leading-normal">
                            Brand Strategy design project for<br>MAKE O.PEACE
                            <span class="hover:underline hidden sm:inline">
                                <br><br>
                                &#8594; Learn More
                            </span>
                        </div>
                    </div>
                    <div class="w-full overflow-hidden mt-[14px] xl:mt-[44px]">
                        <img src="/img/work/mkop/MKOP_WEB-01.jpg" class="w-full transition">
                    </div>
                </NuxtLink>
            </li>
        </ul>
        <!-- <img src="/img/main-logo.svg" class="w-[80vw] lg:w-[600px]"/> -->
    </div>
</template>

<style>
    .line-container {
        position: relative;
    }
    .line {
        width: 100%;
        display: inline-block;
        background: #0025DE;
        position: absolute;
        height: 3px;
        top: 50%;
    }
</style>