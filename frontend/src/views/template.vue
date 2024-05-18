<script setup>
import Your_tool_here from '@/components/your_tool_here.vue';


</script>

<template>

    <!-- component -->
    <div class="max-w-screen-xl mx-auto ">

        <main class="mt-10">
        
            <div class="block lg:flex lg:space-x-2 px-2 lg:p-0 mt-10 mb-10">
                <!-- post cards -->
                <div class="w-full lg:w-2/3">

                    <h1 class="text-3xl md:text-5xl p-2 text-blue-300 tracking-loose">Open Tool Kit</h1>

                    <Your_tool_here />
                    
                </div>

                <!-- right sidebar -->
                <div class="w-full lg:w-1/3 px-3">
                    <!-- topics -->
                    <div class="mb-4">
                        <h5 class="font-bold text-lg uppercase text-gray-50 px-1 mb-2"> Popular Tools </h5>
                        
                        

                    </div>

                    <!-- divider -->
                    <div class="border border-dotted"></div>

                   

                    <!-- divider -->
                    <div class="border border-dotted"></div>

                </div>

            </div>
        </main>
        <!-- main ends here -->

     
    </div>

</template>