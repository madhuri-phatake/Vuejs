<template>
<h1 v-on:mousemove="getConsole()">Home Componets</h1>
<button v-on:click="getData()">ClickMe</button>
<button v-on:dblclick="getData('button double click')">ClickMe</button>
<h1>{{count}}</h1>
</template>
<script>
export default{
    name:"Events",
    data(){
        return{
            count:0
        }
    },
    methods:{
        getData(){
            this.count=this.count+1;
        },
        getConsole(){
            console.warn("function Called");
        }
    },
}
</script>