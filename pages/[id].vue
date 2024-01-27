<template>
    <div>
        

    </div>
    <div class="im">
             <NuxtImg src="https://omaske.ru/wp-content/uploads/2022/11/8265ce4345a7e64db159139d18c7d667.jpeg" />
             </div>
    <div class="container">
    
       
        
          <div class="ct">
            <button class="btn btn-red ">
                <NuxtLink :to="`/${Number(id) - Number(1)}`">Prev</NuxtLink>
            </button>


        <button class="btn btn-green ">
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

display: flex;
  justify-content: center;
   align-items: center;

}
.im{
display: flex;
  justify-content: center;
}
</style>