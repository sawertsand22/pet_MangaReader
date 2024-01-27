<template>
    
    <div>
        <div class="im-p">
         <NuxtImg src="https://n-russia.ru/wp-content/uploads/8/3/a/83af1c24b0f6ec0dc0281e76b31426bc.jpeg"/>
         </div>
        <h2>The name of your Manga</h2>
        <NuxtLink class="btn" to="/1">Read</NuxtLink>
    </div>
</template>

<script setup>
definePageMeta({
    layout: 'read-mange'
})
</script>

<style lang="scss" scoped>
.im-p{
   display: flexbox;
   margin: 20rem 20rem 0;
}
</style>