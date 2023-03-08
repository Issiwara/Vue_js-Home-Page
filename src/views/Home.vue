<script setup>
import TopNavBar from '../components/TopNavBar.vue'
import OffCanvesNavBAr from '../components/OffCanvesNav.vue'
import TopBanner from '../components/TopBanner.vue'
import Banner2 from '../components/Banner2.vue'
import Banner3 from '../components/Banner3.vue'
import SelectionSection from '../components/SelectionSection.vue'
import TitleBox from '../commoncompoet/TitleBox.vue'
import SuggestedSection from '../components/SuggestedSection.vue'
import CardGallery from '../components/CardGallery.vue'
import ShoppingCart from '../commoncompoet/ShoppingCart.vue'
import BottomBanner from '../components/BottomBanner.vue'


components: {
    TopNavBar,
        OffCanvesNavBAr,
        TopBanner,
        Banner2,
        Banner3,
        SelectionSection,
        TitleBox,
        SuggestedSection,
        CardGallery,
        ShoppingCart,
        BottomBanner
}


  // Your component logic here

</script>

<template>
    <div>
        <div class="pl-[57px] pr-[57px] bg-white">
            <TopNavBar class="" />

        </div>

        <div class="bg-[#fff7e8] pl-[57px] pr-[57px] h-[44px]">
            <OffCanvesNavBAr />
        </div>

        <div class="pl-[57px] pr-[57px] mt-1 ">
            <TopBanner />
        </div>
        <div class="flex  pl-[57px] pr-[57px]">
            <Banner2 class="mt-1" />
            <Banner3 class="ml-[26px] mt-1" />
        </div>

        <div class="bg-[#fff7e8] pl-[57px] pt-[1px] pr-[57px] h-[160px] mt-[21px]">
            <SelectionSection class="" />
        </div>

        <div class=" bg-[#ebfdff] pt-[20px] mt-[25px] pl-[57px] pr-[57px]">
            <SuggestedSection />
        </div>

        
        <div class=" bg-[#fff7e8] h-[435px] pt-[20px] mt-[23px] pl-[57px] pr-[57px]">
                <CardGallery/>
        </div>

        <div  class="pl-[57px] pr-[57px] mt-1 ">
            <BottomBanner/>
        </div>

        

    </div>
</template>
