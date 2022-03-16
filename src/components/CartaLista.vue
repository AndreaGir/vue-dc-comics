<template>
    <div class="carta">
        <div class="tuttaimg">
            <img class="immagine" :src="srcThumb" alt="">
        </div>
        
        <h3>{{ title }}</h3>
        
        
       
    </div>
</template>

<script>
export default {
    props: {
        srcThumb: {
            type: String,
            required: true,
        },
        title: {
            type: String,
            required: true,
        },
        price: {
            type: String,
            required: true,
        }
    }
}
</script>

<style lang="scss" scoped>
.carta{
    width: 14%;
    height: max-content;
}
.tuttaimg{
   
}

.immagine{
    width: 100%;
    height: 20%;
}
    
</style>