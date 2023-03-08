<script >
import ShoppingCart from '../commoncompoet/ShoppingCart.vue';
import { Icon } from '@iconify/vue';


export default {
    components: {
        ShoppingCart,
        Arrow: Icon
    },
}



</script>


<template>
    <div class=" ">
        <div class="flex ">
            <div class="flex text-2xl font-bold text-[#6b6d72]">Your have Rencently </div>
            <div class=" pl-4 text-2xl pt-1 underline text-[#6b6d72] font-serif italic font-[550] cursor-pointer">
                View Services!
            </div>
            <p class="pl-[900px] text-[#f57f17] font-semibold cursor-pointer">See All </p>
            <Arrow icon="material-symbols:arrow-forward-ios-sharp" class=" text-[#f57f17] text-xl pt-1"/>
        </div>

        <div class="flex ">
            <ShoppingCart class="mt-[20px] "
                :imageUrl1="'https://img.freepik.com/free-vector/cartoon-web-design-landing-page_52683-70880.jpg?w=2000'"
                imageName="aspen_lipshutz" title=""
                :imageUrl2="' https://en.life-in-germany.de/wp-content/uploads/sites/8/2022/04/portrait-of-a-smiling-businesswoman-SBI-300858611-1.jpg'"
                price="$450" rating="(20)"/>

            <ShoppingCart class="mt-[20px] ml-[47px]"
                :imageUrl1="'https://img.freepik.com/free-vector/cartoon-web-design-background_52683-70879.jpg?w=2000'"
                imageName="terry_donin
    " :imageUrl2="' https://www.africanparks.org/sites/default/files/teaser_image/2022-11/20220916_FOKL_DA%20Lossi.jpg'"
                price="$400" rating="(20)"/>

            <ShoppingCart class="mt-[20px] ml-[47px]"
                :imageUrl1="'https://www.teamsolution.pl/uploads/drive/blog/mobile-first-design/jakosciowe-zdjecia.png'"
                imageName="madelyn_schleifer
    " :imageUrl2="' https://static.dw.com/image/63052755_1006.jpg'" price="$450" rating="(20)"/>

            <ShoppingCart class="mt-[20px] ml-[47px]"
                :imageUrl1="'https://assets.website-files.com/5ff3892e0e1d9f528ef04781/612edeee3fb46e545dcba5c7_Mobile%20website%20design.jpg'"
            imageName="terry_donin"
            :imageUrl2="' https://t4.ftcdn.net/jpg/02/07/26/47/360_F_207264725_F5GohNvyI9nu8HXxKVX4ti95x29x8WvD.jpg'"
            price="$350" rating="(20)"/>

        <ShoppingCart class="mt-[20px] ml-[47px]"
            :imageUrl1="'https://designjobs.com.au/wp-content/uploads/2022/08/mobile-app-design-banner.png'"
            imageName="tiana_bergson"
            :imageUrl2=" 'https://www.babynamespedia.com/z-media/nash-grier/nash-grier-1-thumb.jpg' " price="$200" rating="(20)" />



    </div>

</div></template>