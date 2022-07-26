<template>
<h1>Get input field values</h1>
<input type="text" placeholder="enter the email" v-model="email"/>
<br/><br/>
<input type="password" placeholder="enter the password" v-model="password"/>
<br/><br/>
<button v-on:click="getData()" type="button">Get values</button>
</template>

<script>
export default {
    name:"GetValues",
    data(){
        return{
            email:null,
            password:null,
        }
    },
    methods:{
        getData(){
            document.write("values:",this.email,this.password);
        }
    }
}
</script>