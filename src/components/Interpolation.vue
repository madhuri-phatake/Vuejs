<template>
<h1>Email:{{email}}</h1>
<h1>Name:{{getName('peter')}}</h1>
</template>
<script>
export default{
    name:'Home',
    data(){
            return{
                email:"madhu@gmail.com"
            }
    },
    methods: {
                getName(name){
                return name
                }  
    },
}
</script>
<style scoped>
h1{
    color: blue;
}
</style>