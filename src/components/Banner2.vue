<script>
import { Icon } from '@iconify/vue';

export default {
    components: {
        addUser: Icon
    }
}
</script>

<template>
    <div class="w-[279px] h-[256px] pt-[40px] bg-white shadow-md border mt-2 grid justify-items-center cursor-pointer">
        <img src="https://tiejet.com/image/images/kZ2blIPBtnNSVqrWL8URHPMxYnztgKJyI4RBz9sA.png?p=logo"
            class=" brand-logo h-[30px]  w-[100px] " alt="Logo" title="Logo">
        <p class="text-2xl font-bold absolute mt-[42px] pl-[8px] text-[#404145]">Tiejet,</p>
        <p class="absolute pt-[84px]">Business balance: $268.74</p>

        <div class="flex mt-[125px] absolute  ml-[25px]">
            <img class="inline-block object-cover w-9 h-9 rounded-full"
                src="https://images.pexels.com/photos/2955305/pexels-photo-2955305.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
                alt="Profile image" />
            
                <div class="w-9 h-9 border rounded-full pl-2 ml-2 pt-1">
                    <addUser icon="heroicons:user-plus" class="rounded-full font-bold absolute text-xl mt-[4px]  text-[#74767e]" />
                </div>
                

        </div>
    </div>
</template>