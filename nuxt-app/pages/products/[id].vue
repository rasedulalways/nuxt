<template>
    <div>
        <!-- <p> Product details for id: {{ $route.params.id }} </p> -->
        <p> Product details for {{ id }}</p>

        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nemo officiis eos deleniti, ex omnis exercitationem inventore, possimus dolore vel laborum, reiciendis facere cum quibusdam eaque? Fugiat aliquam perspiciatis exercitationem aut.</p>
    </div>
</template>

<script setup>
    const{ id } = useRoute().params

    definePageMeta({
        layout: 'products'
    })
</script>

<style scoped>

</style>