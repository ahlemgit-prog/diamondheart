
import type { Link } from 'nuxt/dist/head/runtime/components';

import type { NuxtImg } from 'nuxt/dist/app/components/nuxt-stubs';

<template>
    <nav class="bg-gray-950">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-0">
                <div class="flex items-center justify-between h-16">
                    <div class="flex items-center">
                        <div class="flex-shrink-0">
                            <NuxtLink to="/" class="text-white">
                                    <NuxtImg 
                                        class="relative dark:drop-shadow-[0_0_0.3rem_#020617]" 
                                        src="/diamond-logo.svg" 
                                        alt="Diamond Heart Logo" 
                                        quality="80" 
                                        width="75" 
                                        height="40" 
                                        priority
                                        />      
                            </NuxtLink>
                        </div>
                    </div>
                    <div class="hidden md:block">
                        <div class="ml-4 flex items-center space-x-4">
                        <ul>
                            <li class="list-none">
                               <NuxtLink to="/" class="link-navbar">New</NuxtLink>
                               <NuxtLink to="/about" class="link-navbar">About</NuxtLink>
                               <NuxtLink to="/jewels" class="link-navbar">Jewels</NuxtLink>
                               <NuxtLink to="/contact" class="link-navbar">Contact</NuxtLink> 
                            </li>
                        </ul>     
                               
                        </div>
                    </div>
                    
                    <div class="md:hidden flex items-center" @click="toggleMobileMenu" v-show="mobile" >
    
                        <button class="inline-flex items-center justify-center p- rounded-md text-white hover:text-white focus:outline-none focus:ring-2 focus:ring-inset focus:ring-white"
                        >
                            <i class="gg-menu-right" :class="{ 'icon-active': mobileNav}"></i>
                        </button>
                        
                    </div>
                </div>
            </div>
                <div class="md:hidden" v-show="mobileNav">
                        <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                            <NuxtLink to="/" class="link-navbar-mobile">New</NuxtLink>
                            <NuxtLink to="/about" class="link-navbar-mobile">About</NuxtLink>
                            <NuxtLink to="/jewels" class="link-navbar-mobile">Jewels</NuxtLink>
                            <NuxtLink to="/contact" class="link-navbar-mobile">Contact</NuxtLink>
                        </div>
                </div>
        </nav>
</template>
<script>
export default {
    data () {
        return {
            mobile: true,
            mobileNav: null,
        };
    },
    methods: {
        toggleMobileMenu () {
            this.mobileNav = !this.mobileNav
        },
    },
};

</script>