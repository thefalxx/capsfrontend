<template>

<!-- Page Main -->

    <!-- Hero -->
    <main class="flex flex-col items-center justify-center mt-32">
    <section
        class="flex flex-wrap items-center -mx-3 font-sans px-4 w-full lg:max-w-screen-lg sm:max-w-screen-sm md:max-w-screen-md pb-20">
        <!-- Column-1 -->
        <div class="px-3 w-full lg:w-2/5 pl-20">
            <div
                class="mx-auto mb-8 max-w-lg text-center lg:mx-0 lg:max-w-md lg:text-left">
                <h2 class="mb-4 text-3xl font-bold text-left lg:text-5xl">
                    <!--text here-->

                    <span class="text-5xl text-teal-800 leading-relaxeds"
                        > Scan N' Savor
                    </span>
                </h2>

                <p
                    class="visible mx-0 mt-3 mb-0 text-sm leading-relaxed text-left text-slate-400">
                    A first-class dining experience integrated with QR Technology
                </p>
            </div>

            <div class="text-center lg:text-left">
                <a
                    class="block visible py-4 px-8 mb-4 text-s font-semibold tracking-wide leading-none text-white bg-teal-800 rounded cursor-pointer sm:mr-3 sm:mb-0 sm:inline-block"
                    @click="navigateTo('createacc')"
                    >Get Started</a
                >
            </div>
        </div>

        <div class=" flex flex-wrap px-3 mb-12 w-full lg:mb-0 lg:w-3/5 pl-20">
                <div class="flex justify-center items-center ">
                    <div class="justify-center flex-1 mb-10 md:mb-16 lg:mb-0 z-10 block max-w-full h-auto align-middle lg:max-w-lg">
                        <img class="wsm:w-full sm:h-auto md:w-full md:h-auto" 
                        src="../images/ee17dfb827a8930850e4d9b265cf9c4c-removebg-preview 1.png" 
                        alt="image"/>
                    </div>
                </div>
            </div> 
    </section>

    <!-- Parallax Background -->
    <section id="service"
        class="flex flex-col w-full h-[500px] bg-cover bg-fixed bg-center justify-center pl-10"
        style="
             background: #265A5B;
        ">

        <div>

        </div>


        <h1 class="text-white text-5xl font-bold mb-10 pl-5 pt-10 ">
            Looking for some place to dine in?
        </h1>

        <span class="text-left pl-5 justify-center font-small my-20 text-white/90">
            <p>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor 
                <br>incididunt ut labore et dolore magna aliqua.
                 <br>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. 
                 <br>Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. 
                 <br>Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
            </p>


        </span>  

    </section>

    <section >
        <div>
            <div class="pt-10">
                <img class="" src="../images/Group 87.png" alt="image">


            </div>
        </div>
    </section>


</main>
 

</template>

<script setup>
definePageMeta({
    layout:"navbar"
    
})

</script>


