<template>
    <div>
        <header>
            <button class="btn btn-back">
            <NuxtLink to="/">Back</NuxtLink>
            </button>
        </header>
    </div>
    
        <slot/>
    
</template>

<script setup>

</script>

<style lang="scss" scoped>
div{
    background-color: black;
}
</style>