<template>
    
    <main class="">
            <Navbar />

            <div class="grid-main mx-4">

                <!-- IMAGE PRINCIPAL  -->
                <div class="">
                    <NuxtImg 
                        class="block justify-center mx-auto py-20" 
                        src="/draw.webp" 
                        alt="Draw Image" 
                        quality="80" 
                        width="500" 
                        height="500" 
                        priority
                    /> 
                </div> 

                <!-- TITRE PRINCIPAL -->
                <div class="flex justify-center">
                    <div class="mx-auto md:pt-20 lg:pt-18 sm:items-center">
                        <div class="px-20">
                            <h2 class="title-header pb-4 text-3xl">
                                Who Are We
                            </h2>
                            <p class='title-header text-3xl'><span class="myFont animate-pulse"> Diamond Heart</span></p>
                        </div>
                        <div class="grid grid-cols-1 pt-7 pb-14">
                            <!-- SECTION FORM -->
                            <section class="container">
                                <div class="grid-about pb-9">
                                    <p class="text-gray-900 dark:text-gray-200 leading-9 text-lg px-20">
                                        At Diamond Heart, we have a workshop in Belgium where 20 qualified craftsmen work.
                                        Using both traditional tools and cutting-edge tools,
                                        the latter carry out repair,
                                        transformation,
                                        enhancement,
                                        customization operations and
                                        can even create the jewelry of your dreams.
                                    </p>
                                </div>
                            </section>
                        </div>
                    </div>
                </div>
            </div>
            <Footer />
        </main>
</template>