
<template>
  <main class="mx-auto">

<!-- NAVBAR -->
<Navbar />

<div class="grid-main">

  <!-- IMAGE PRINCIPAL -->
  <div class="mx-auto">
    <NuxtLink to="/new/[id].vue">
      <NuxtImg 
          class="block justify-center mx-auto" 
          src="/bague.webp" 
          alt="Diamond Heart Ring" 
          quality="80" 
          width="350" 
          height="350" 
          priority
          />
    </NuxtLink>    
  </div>

  <!-- TITRE PRINCIPAL -->
  <div class="flex justify-center">
    <div class="mx-auto md:pt-20 lg:pt-18 sm:items-center">
      <div>
        <h2 class="title-header pb-4">
          Special Celebration
        </h2>
        <p class='title-header'>with <span class="myFont animate-pulse"> Diamond Heart</span></p>
      </div>
      <div class="grid grid-cols-1 pt-7 pb-14">
          <NuxtLink to="/new/[id].vue">
            <button type="button" class="button">
              Learn More
            </button>
          </NuxtLink>
      </div>
    </div>
  </div>
</div>

<!-- SECOND MAIN -->
<div>
  <div class="col-start-1 col-end-7 block p-16 bg-gray-500 dark:bg-gray-800">
    <div class="grid-second-main">
      <div class="text-white">
        <div class="">
          <NuxtLink to="/">
            <NuxtImg 
              class="card" 
              src="/bague-1.webp" 
              alt="Bague Argent Image" 
              quality="80" 
              width="300" 
              height="300" 
              priority
              /> 
          </NuxtLink>
        </div>
      </div>

      <div class="text-white">
        <div classN="">
          <NuxtLink to="/">
            <NuxtImg 
              class="card" 
              src="/bague-2.webp" 
              alt="Bague Argent Image" 
              quality="80" 
              width="300" 
              height="300" 
              priority
              /> 
          </NuxtLink>
        </div>
      </div>

      <div class="text-white">
        <div class="">
          <NuxtLink to="/">
            <NuxtImg 
              class="card" 
              src="/bague-3.webp" 
              alt="Bague Argent Image" 
              quality="80" 
              width="300" 
              height="300" 
              priority
              /> 
          </NuxtLink>
        </div>
      </div>
    </div>
  </div>
</div>
<Footer />
</main >
</template>

