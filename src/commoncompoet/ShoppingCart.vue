<script scoped>
import { Icon } from '@iconify/vue';

export default {
    components: {
        Star: Icon
    },
    props: {
        imageUrl1: String,
        imageUrl2: String,
        imageName: String,
        title: String,
        price: String,
        rating: String,

    },


};

</script>

<template>
    <div class="w-[245px] h-[342px] bg-white border rounded-sm cursor-pointer hover:scale-105 hover: duration-150 " >
        <div>

            <img :src="imageUrl1" alt="My Image" class="h-[148px] w-[245px]" />

            <!--<img src="https://img.freepik.com/free-vector/cartoon-web-design-landing-page_52683-70880.jpg?t=st=1677948029~exp=1677948629~hmac=329f25e61317f39102852305bfab2343c040f651800a9a7be5849d10c8ef3692"
                                alt="" class=""> -->

        </div>
        <div class="flex ">
            <div class="relative inline-block mt-[10px]  ml-[11px]">
                <img sr>
                <img class="inline-block object-cover w-7 h-7 rounded-full" :src="imageUrl2" alt="Profile image" />
                <span
                    class="absolute bottom-[20px]  right-0 inline-block w-[10px] h-[10px] bg-green-600 border-2 border-white rounded-full"></span>
            </div>
            <div class="pl-2 pt-2 font-semibold text-neutral-800">{{ imageName }}</div>
        </div>
        <div class="font-semibold text-[#6b6d72] pl-3 pt-[22px]">{{ title }}I will design interactive<br>

            mobile app Ux ui</div>

        <div class="flex ml-[8px] mt-3">
            <Star icon="material-symbols:star" class="h-[24px] w-[26px]" color="#f57f17" />

            <div class="text-[#f57f17] pl-[5px] font-semibold ">5.0</div>
            <div class="pl-1 text-[#6b6d72] ">{{ rating }}</div>

        </div>
        <div class="w-full h-[1px] mt-2 bg-[#e6e6e6]"></div>

        <div class="flex">
            <div class="flex pt-2 pl-2">
                <Star icon="ph:list-bold" class="text-2xl  text-[#6b6d72]" />
                <Star icon="mdi:cards-heart" class="text-2xl text-[#6b6d72]" />
                <p class=" pl-[48px] text-[#6b6d72] font-semibold pt-1 text-xs ">STARTING AT</p>

            </div>
            <P class="font-semibold text-[#6b6d72] pl-2  pb-10  text-xl pt-1 capitalize">{{ price }}</P>
        </div>

    </div>
</template>