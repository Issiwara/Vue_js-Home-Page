<script >
import myImage from '../assets/cicles.svg';
import { Icon } from '@iconify/vue';

export default {
    data() {
        return {
            imageSrc: myImage,
            Icon
        }
    }, components: {
        hicon: Icon,
        

    },
};
</script>

<template>
    <div class="flex " >
        <!-- Off Canves Nav Bar -->
  
        <img src="https://tiejet.com/image/images/kZ2blIPBtnNSVqrWL8URHPMxYnztgKJyI4RBz9sA.png?p=logo" class="brand-logo h-[35px] w-[119px] mt-[20px]" alt="Logo" title="Logo">
        <p class="bg-transparent font-semibold mt-[25px] text-lg text-[#090909] ml-[18px] pr-[31px]">Business</p>
        <div class="bg-white h-[44px]  rounded-md flex mb-[20px] mt-[20px] ">

            <div class="flex w-[631px]  rounded-r-md h-[44px] outline-1 border ">
                <input type="text" class="px-4 py-2 h-[44px] rounded-l-sm  w-[445px] border focus:outline-none "
                    placeholder="What service are you looking for today ?">


                <button id="drop-down " class="w-[131px]  bg-white  outline-0 h-[44px] text-[#74767e] border ">
                    <select class="focus:outline-none">
                        <option>All Services</option>
                        <option>India</option>
                        <option>Bangladesh</option>
                    </select>
                </button>

                <button class="w-[60px] h-[44px] px-4 rounded-r-md outline-1 bg-[#f57f17]  ">
                    <svg class="w-6 h-6 text-white bg-transparent" fill="currentColor" xmlns="http://www.w3.org/2000/svg"
                        viewBox="0 0 24 24">
                        <path
                            d="M16.32 14.9l5.39 5.4a1 1 0 0 1-1.42 1.4l-5.38-5.38a8 8 0 1 1 1.41-1.41zM10 16a6 6 0 1 0 0-12 6 6 0 0 0 0 12z" />
                    </svg>
                </button>
            </div>

        </div>

        <div class="bg-white ml-[40px] mt-[25px]  text-lg h-[44px] ">
            <button id="drop-down " class="w-[131px]  text-[#74767e] font-semibold focus:outline-none  ">
                <select class="focus:outline-none">
                    <option>My Business</option>
                    <option>India</option>
                    <option>Bangladesh</option>
                </select>
            </button>
        </div>

        <p class="ml-[25px]  mt-[25px] text-[#74767e] font-semibold text-lg cursor-pointer">Freelancers</p>

        <p class=" ml-[25px]   mt-[25px] text-[#74767e] font-semibold text-lg pl-4 cursor-pointer">Orders</p>


        <hicon icon="mdi:bell-outline" class="text-2xl mt-[26px]  ml-[25px] font-semibold text-[#74767e] cursor-pointer" />
        <hicon icon="wpf:message-outline"  class="text-2xl mt-[26px] ml-[25px] font-semibold text-[#74767e] cursor-pointer"/>

        <!-- Code block starts -->
        
        <div class="relative inline-block mt-[18px]  ml-[25px] cursor-pointer">
            <img class="inline-block object-cover w-9 h-9 rounded-full"
                src="https://images.pexels.com/photos/2955305/pexels-photo-2955305.jpeg?auto=compress&cs=tinysrgb&h=650&w=940"
                alt="Profile image" />
            <span
                class="absolute bottom-[54px]  right-0 inline-block w-3 h-3 bg-green-600 border-2 border-white rounded-full"></span>
        </div>

    </div>
</template>