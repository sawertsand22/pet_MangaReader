<template>
    <div>
        

    </div>

    <div>
        <container>

            <button class="btn btn-red ct">
                <NuxtLink :to="`/${Number(id) - Number(1)}`">Prev</NuxtLink>
            </button>


        <button class="btn btn-green ct">
            <NuxtLink   :to="`/${Number(id)+Number(1)}`">Next</NuxtLink>
        </button>
        
        </container>
    </div>
</template>

<script setup>
const {id} = useRoute().params
definePageMeta({
    layout: 'on-reading-manga'
})

</script>

<style lang="scss" scoped>
.ct{
 
display:inline-block;
margin-left: auto;
margin-right: 50px;
 
}

</style>