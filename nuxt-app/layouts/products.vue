<template>
    <div class="">   
        <header>
            <nav>
                <NuxtLink to="/products"> Nuxt Dojo Merch </NuxtLink>
            </nav>
        </header>     

        <!-- output the page content -->
        <div>
            <slot />
        </div>

        <footer class="py-2 text-lg bg-slate-300">
            <ul>
                <li class="inline-block mx-4"><NuxtLink to="/">Home</NuxtLink></li>
                <li class="inline-block mx-4"><NuxtLink to="/about">About</NuxtLink></li>
                <li class="inline-block mx-4"><NuxtLink to="/products">Products</NuxtLink></li>
            </ul>
        </footer>
    </div>
</template>


<script setup>
    
</script>

<style scioed>
    .router-link-exact-active {
        color: #12b488;
    }
</style>