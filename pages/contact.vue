<template>
     <main>
            <Navbar />
            <div class="grid-contact">
                <div class="container">

                    <!-- TITRE PRINCIPAL -->
                    <div class="flex justify-center">
                        <div class="mx-auto lg:my-12 sm:items-center">
                            <div class="my-7">
                                <h2 class="title-header pb-4 text-3xl">
                                    Get In Touch
                                </h2>
                                <p class='title-header text-3xl'>with <span class="myFont animate-pulse"> Diamond Heart</span></p>
                            </div>
                        </div>
                    </div>

                    <!-- CONTACT FORM -->
                    <form class="container">
                        <div class="grid gap-6 mb-6 md:grid-cols-2">
                            <div>
                                <label htmlFor="first_name" class="form-label">First name</label>
                                <input type="text" id="first_name" class="form-input" placeholder="John" required />
                            </div>
                            <div>
                                <label htmlFor="last_name" class="form-label">Last name</label>
                                <input type="text" id="last_name" class="form-input" placeholder="Doe" required />
                            </div>
                            <div>
                                <label htmlFor="phone" class="form-label">Phone number</label>
                                <input type="tel" id="phone" class="form-input" placeholder="+32" pattern="[0-9]{3}-[0-9]{2}-[0-9]{3}" required />
                            </div>
                            <div>
                                <label htmlFor="email" class="form-label">Email</label>
                                <input type="email" id="email" class="form-input" placeholder="@gmail.com" required />
                            </div>
                        </div>
                        <div class="mb-6">
                            <label htmlFor="message" class="block mb-2 text-sm font-medium text-gray-900 dark:text-white">Message</label>
                            <textarea id="message" class="form-input" placeholder="Hello," required ></textarea>
                        </div>

                        <button type="submit" class="button grid grid-cols-1 pt-7 pb-14">Submit</button>
                    </form>
                </div>

                <div class="div">

                    <!-- IMAGE PRINCIPAL -->
                    <div class="">
                        <NuxtImg 
                        class="block justify-center mx-auto py-20" 
                        src="/contact.webp" 
                        alt="Contact Image" 
                        quality="80" 
                        width="400" 
                        height="600" 
                        priority
                        /> 
                    </div>
                </div>
            </div>
            <Footer />
        </main>
</template>