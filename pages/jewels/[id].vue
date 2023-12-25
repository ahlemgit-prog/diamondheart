
<template>
    <main>
            <Navbar />
            <div class="grid-main mx-4">

                <!-- IMAGE PRINCIPAL -->
                <div class="">
                    <NuxtImg 
                        class="block justify-center mx-auto py-20 scale-75 hover:scale-95 ease-in duration-500" 
                        src="/6.webp" 
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
                            <h2 class="title-header pb-4 text-3xl ">
                                Brillant Gold
                            </h2>
                            <p class='title-header text-3xl'><span class="myFont animate-pulse"> Diamond Heart</span></p>
                        </div>
                        <div class="grid grid-cols-1 pt-7 pb-14">
                            <!-- SECTION FORM -->
                            <section class="container">
                                <div class="grid-about">
                                    <div class="grid grid-cols-3 gap-4">

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Weight (gr)
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                0.905
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Main material
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                Gold
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Color
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                Rose & White
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Diamond's color
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                White
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Number of stones
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                7
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Shape
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                Round
                                            </p>
                                        </div>

                                        <div class="col-span-2">
                                            <p class="text-article-left">
                                                Carat
                                            </p>
                                        </div>
                                        <div class="">
                                            <p class="text-article-right">
                                                0.0350
                                            </p>
                                        </div>
                                        <hr />


                                    </div>
                                    <!-- PRIZE -->

                                    <div class="">
                                        <p class="text-neutral-950 dark:text-gray-100 leading-9 text-2xl py-1">
                                            257 $
                                        </p>
                                    </div>
                                    <div class="grid grid-cols-1 pt-7 pb-14">
                                            <NuxtLink to="/contact">
                                                <button type="button" class="button">
                                                    Make An Appointment
                                                </button>
                                            </NuxtLink>
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


