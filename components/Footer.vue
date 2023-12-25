
import type { Link } from 'nuxt/dist/head/runtime/components';

import type { NuxtImg } from 'nuxt/dist/app/components/nuxt-stubs';

<template>
     <main class="mx-auto bg-gray-950">
            <div class="grid-footer lg:p-24 md:p-20 p-16">

                <!-- FIRST SECTION -->
                <div class="grid-element">
                    <h3 class="title-footer">DIAMOND HEART</h3>
                    <nav class="">
                        <ul>
                            <li class="list-none flex flex-col bg-gray-950 text-white border-gray-200">
                               <NuxtLink to="/legal-notice" class="link-footer">Legal Notice</NuxtLink>
                               <NuxtLink to="/privacy-policy" class="link-footer">Privacy Policy</NuxtLink>
                            </li>
                        </ul>  
                    </nav>
                </div>

                <!-- SECOND SECTION -->
                <div class="grid-element">
                    <h3 class="title-footer">SHOP</h3>
                    <nav class="">
                        <ul>
                            <li class="list-none flex flex-col bg-gray-950 text-white border-gray-200">
                               <NuxtLink to="/" class="link-footer">New</NuxtLink>
                               <NuxtLink to="/about" class="link-footer">About</NuxtLink>
                               <NuxtLink to="/jewels" class="link-footer">Jewels</NuxtLink>
                               <NuxtLink to="/contact" class="link-footer">Contact</NuxtLink> 
                            </li>
                        </ul>  
                    </nav>
                </div>

                <!-- THIRD SECTION -->
                <div class="grid-element">
                    <h3 class="title-footer">CONTACT</h3>
                    <div class="flex flex-col bg-gray-950 text-white border-gray-200">

                        <div class="text-gray-300 hover:text-gray-200 link-element flex">
                            <span class="">
                                    <i class="gg-phone animate-wiggle"></i>
                            </span>
                            <span class="shrink-0 h-9 w-32">
                                <NuxtLink to="tel:+324 00 00 00 00" class="flex flex-row-reverse link-element">
                                    +32 4 00 00 00 00
                                </NuxtLink>
                            </span>
                        </div>

                        <div class="text-gray-300 hover:text-gray-200 link-element flex">
                            <span class="">
                                <NuxtLink to="mailto:DiamondVibrateHeart@gmail.com" class="text-white">
                                    <NuxtImg 
                                        class="relative dark:drop-shadow-[0_0_0.3rem_#020617]" 
                                        src="/envelope-regular.svg" 
                                        alt="Envelope Icon" 
                                        quality="80" 
                                        width="25" 
                                        height="25" 
                                        priority
                                        />      
                                 </NuxtLink>
                                
                            </span>
                            <span class="ml-3 mt-1">
                                <NuxtLink to="mailto:DVH@gmail.com" class="flex flex-row-reverse link-element">
                                     DVH@gmail.com
                                </NuxtLink>
                                
                            </span>
                        </div>

                        <div class="text-gray-300 hover:text-gray-200 link-element flex">
                            <span class="mt-4">
                                <NuxtLink to="https://www.google.com/maps" class="text-white">
                                    <NuxtImg 
                                        class="relative dark:drop-shadow-[0_0_0.3rem_#020617]" 
                                        src="/pin.svg" 
                                        alt="Map Icon" 
                                        quality="80" 
                                        width="25" 
                                        height="25" 
                                        priority
                                        />      
                                 </NuxtLink>

                            </span>
                            <span class="ml-3 mt-1">
                                <NuxtLink to="https://www.google.com/maps" class="text-white">
                                    <p class="flex flex-row-reverse link-element mt-4">Rue Figure 7, 4000 L.G</p>
                                </NuxtLink>
                            </span>
                        </div>

                    </div>
                </div>

                <!-- FOURTH SECTION -->
                <div class="grid-element">
                    <h3 class="title-footer">FOLLOW US</h3>
                    <div class="social-footer flex flex-wrap">
                        <div class="text-white link-footer">
                            
                            <NuxtLink to="/" class="">
                                <i class="gg-facebook hover:text-gray-400 px-4"></i>
                            </NuxtLink>
                            
                        </div>

                        <div class="text-white link-footer">
                            
                            <NuxtLink to="/" class="r">
                                <i class="gg-instagram hover:text-gray-400"></i>
                            </NuxtLink>
                            
                        </div>
                    </div>
                </div>

            </div>

            <!-- COPYRIGHT -->
            <div class="col-start-1 col-end-7">
                <p class="text-center text-xs py-8 text-gray-200">&copy; 2023 Diamond Heart. All Rights Reserved</p>
            </div>
        </main>
</template>
