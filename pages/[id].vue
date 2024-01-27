<template>
    <div>
        

    </div>

    <div class="container">
    
        <div class="ct">
         <img scr="~/assets/img/1.png" alt=""/>
            <button class="btn btn-red ct">
                <NuxtLink :to="`/${Number(id) - Number(1)}`">Prev</NuxtLink>
            </button>


        <button class="btn btn-green ct">
            <NuxtLink   :to="`/${Number(id)+Number(1)}`">Next</NuxtLink>
        </button>
        </div>
        
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

text-align: center;
margin: 0 auto;

}
div {

}
</style>