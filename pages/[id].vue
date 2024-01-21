<template>
    <div>
        <button class="btn btn-green">
<NuxtLink   :to="`/${Number(id)+Number(1)}`">Next</NuxtLink>
</button>

    <button class="btn btn-red">
<NuxtLink :to="`/${Number(id)-Number(1)}`">Prev</NuxtLink>
    </button>
    </div>
</template>

<script setup>
const {id} = useRoute().params
definePageMeta({
    layout: 'on-reading-manga'
})

</script>

<style lang="scss" scoped>

</style>