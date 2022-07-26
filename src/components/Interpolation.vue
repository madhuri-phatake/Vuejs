<template>
<h1>Email:{{email}}</h1>
<!-- <h1>{{this.email}}</h1> -->
<button v-on:click="changeEnmail('v@gmail.com')">click me</button>
<!-- <h1>Name:{{getName('peter')}}</h1> -->
</template>
<script>
export default{
    name:'Home',
    data(){
            return{
                email:"madhu@gmail.com"
            }
    },
    methods:{
                changeEnmail(name){
                this.email = name;
                },
                // getEmail(email){
                //     return email;
                // }
    },
}
</script>
<style scoped>
h1{
    color: blue;
}
</style>