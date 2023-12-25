<template>
    <main>
            <Navbar />
            <div class="grid-main mx-4">

                <!-- IMAGE PRINCIPAL -->
                <div class="">
                    <NuxtImg 
                        class="block justify-center mx-auto py-20 scale-75 hover:scale-95 ease-in duration-500" 
                        src="/bague.webp" 
                        alt="6" 
                        quality="80" 
                        width="670" 
                        height="670" 
                        priority
                        /> 
                </div>

                <!-- TITRE PRINCIPAL -->
                <div class="flex justify-center">
                    <div class="mx-auto md:pt-20 lg:pt-18 sm:items-center">
                        <div>
                            <h2 class="title-header pb-4 text-3xl">
                                Light
                            </h2>
                            <p class='title-header text-3xl'><span class="myFont animate-pulse"> Diamond Heart</span></p>
                        </div>
                        <div class="grid grid-cols-1 pt-7 pb-14">
                            <!-- SECTION FORM -->
                            <section class="container">
                                <div class="grid-about">
                                    <div class="grid grid-cols-3 gap-4">

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Weight (gr)
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                1
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Main material
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                Gold
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Color
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                White
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Diamond's color
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                White
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Number of stones
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                7
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Shape
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                Round
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-gray-400 dark:text-gray-400 leading-9 text-md">
                                                Carat
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-gray-950 dark:text-gray-300 leading-9 text-md">
                                                0.19
                                            </p>
                                        </div>
                                        <hr />


                                    </div>
                                    <!-- PRIZE -->

                                    <div class="">
                                        <p class="text-neutral-950 dark:text-gray-100 leading-9 text-2xl py-1">
                                            3 418 $
                                        </p>
                                    </div>
                                    <div class="grid grid-cols-1 pt-7 pb-14">
                                        <button type="button" class="button">
                                            <NuxtLink to="/contact">Make An Appointment</NuxtLink>
                                        </button>
                                    </div>

                                </div>
                            </section>
                        </div>
                    </div>
                </div>
            </div>
            <Footer />
        </main>
</template>