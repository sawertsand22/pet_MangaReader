<template>
    <body>
    <div>
        <div class="im-p">
         <NuxtImg src="https://n-russia.ru/wp-content/uploads/8/3/a/83af1c24b0f6ec0dc0281e76b31426bc.jpeg"/>
         </div>
         <div>
        <h2>The name of your Manga</h2>
        </div>
        <br>
        <NuxtLink class="btn btn-back" to="/1">Read</NuxtLink>
    </div>
    </body>
</template>

<script setup>
definePageMeta({
    layout: 'read-mange'
})
</script>

<style lang="scss" scoped>
.im-p{
   background: no-repeat;
   margin: 0 20rem  0 25rem;

}
body{
    background-color: black;
}
h2{
    color: white;
}
</style>