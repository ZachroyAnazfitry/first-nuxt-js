<template>
    <!-- testing navigation power of Nuxt -->
    <header class="shadow-sm bg-white">
        <nav class="container mx-auto p-4 flex justify-between">
            <ul>
                <li class="flex ">
                    <NuxtLink class="p-2" to="/">Home</NuxtLink>
                    <NuxtLink class="p-2" to="/about">About</NuxtLink>
                </li>
              
            </ul>
        </nav>

    </header>

    <div class="container p-4">

        
        <!-- slot is a placeholder -->
        <slot/>
    </div>
    
</template>

<style scoped>
/* highlight the selected route */
    .router-link-exact-active {
        color: #12b488;
    }
</style>