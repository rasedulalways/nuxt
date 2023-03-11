<template>
    <div class="">
        <header>
            <nav class="py-2 text-lg bg-gray-200">
                <ul>
                    <li class="inline-block mx-4"><NuxtLink to="/">Home</NuxtLink></li>
                    <li class="inline-block mx-4"><NuxtLink to="/about">About</NuxtLink></li>
                    <li class="inline-block mx-4"><NuxtLink to="/products">Products</NuxtLink></li>
                </ul>
            </nav>
        </header>

        <!-- output the page content -->
        <div>
            <slot />
        </div>
    </div>
</template>


<script setup>
    
</script>

<style scioed>
    .router-link-exact-active {
        color: #12b488;
    }
</style>