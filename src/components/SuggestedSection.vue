<script>
import { Icon } from '@iconify/vue';

export default {
    components: {
        Arrow: Icon
    }
}
</script>



<template>
    <div>
        <div class="flex pt-[16px] text-[#6b6d72] ">
            <div class="text-2xl font-bold ">What do you want to </div>
            <div class="font-serif font-semibold underline italic text-2xl pl-3 cursor-pointer">do today?</div>
            <div class="pl-[960px] font-semibold text-[#f57f17]">See All </div>  <Arrow class=" text-[#f57f17] pt-[6px] font-extrabold text-xl" icon="material-symbols:arrow-forward-ios-sharp" />

        </div>


        <div class="flex gap-[28px] pt-[33px] pb-[35px] ">

            <div class="w-[330px] h-[253px] border border-zinc-200 shadow-sm bg-white hover:scale-105 hover: duration-150 cursor-pointer ">
                <div class="bg-[#ff62ab] 50 w-[330px] h-[3px]"></div>
                <p class="text-[#ff62ab] pt-[24px] pl-[220px]  font-bold">SUGGESTED</p>
                <p class="pt-[40px] pl-[24px]">LOGO</p>

                <p class="font-semibold text-[#404145] text-2xl pt-[14px] pl-[24px]">Business Brading</p>
                <div class="flex pt-[47px] font-semibold text-[#f57f17] pl-[24px]">
                    <div class="">All Service Offer </div>
                    
                        <Arrow icon="material-symbols:arrow-forward-ios-sharp" class=" font-[1100] pt-[7px] pl-1 text-[20px]"/>
                    
                </div>

            </div>

            <div class="w-[330px] h-[253px] border bg-white border-zinc-200 shadow-sm hover:scale-105 hover: duration-150 cursor-pointer ">
                <div class="bg-[#f57f17] 50 w-[330px] h-[3px] "></div>
                <p class="text-[#f57f17] pt-[24px] pl-[220px]  font-bold">SUGGESTED</p>
                <p class="pt-[40px] pl-[24px]">LOGO</p>

                <p class="font-semibold text-[#404145] text-2xl pt-[14px] pl-[24px]">Digital Marketing</p>
                <div class="flex pt-[47px] font-semibold text-[#f57f17] pl-[24px]">
                    <div class="">All Service Offer </div>
                    <Arrow icon="material-symbols:arrow-forward-ios-sharp" class=" font-[1100] pt-[7px] pl-1 text-[20px]"/>
                </div>


            </div>
            <div class="w-[330px] h-[253px] border bg-white border-zinc-200 shadow-sm hover:scale-105 hover: duration-150 cursor-pointer4 ">
                <div class="bg-[#15bf77] 50 w-[330px] h-[3px]"></div>
                <p class="text-[#15bf77] pt-[24px] pl-[220px]  font-bold">SUGGESTED</p>
                <p class="pt-[40px] pl-[24px]">LOGO</p>

                <p class="font-semibold text-[#404145] text-2xl pt-[14px] pl-[24px]">Increase Business Sales</p>
                <div class="flex pt-[47px] font-semibold text-[#f57f17] pl-[24px]">
                    <div class="">All Service Offer </div>
                    <Arrow icon="material-symbols:arrow-forward-ios-sharp" class=" font-[1100] pt-[7px] pl-1 text-[20px]"/>
                </div>


            </div>
            <div class="w-[330px] h-[253px] border bg-white border-zinc-200 shadow-sm hover:scale-105 hover: duration-150 cursor-pointer ">
                <div class="bg-[#426ee4] 50 w-[330px] h-[3px]"></div>
                <p class="text-[#426ee4] pt-[24px] pl-[220px]  font-bold">SUGGESTED</p>
                <p class="pt-[40px] pl-[24px]">LOGO</p>

                <p class="font-semibold text-[#404145] text-2xl pt-[14px] pl-[24px]">Create Social Media</p>
                <div class="flex pt-[47px] font-semibold text-[#f57f17] pl-[24px]">
                    <div class="">All Service Offer </div>
                    <Arrow icon="material-symbols:arrow-forward-ios-sharp" class=" font-[1100] pt-[7px] pl-1 text-[20px]"/>
                </div>


            </div>

        </div>

    </div>
</template>