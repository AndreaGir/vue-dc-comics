<template>
    <div class="carta">
        <img :src="srcThumb" alt="">
        <h3>{{ title }}</h3>
        
       <span>{{price}}</span>
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

</style>