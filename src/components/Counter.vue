<template>
    <div>
        <h1>This is a Counter.</h1>
        <p @click="increment"> Click me to increment.</p>
        <p>  You have Clicked {{ total }} Times. </p>
    </div>
</template>

<script>

export default {
    name:'Counter',
    data(){
        return{
            total:0
        }
    },
    methods:{
        increment(){
            return this.total += 1;
        }
    }
}
</script>

<style scoped>

</style>
