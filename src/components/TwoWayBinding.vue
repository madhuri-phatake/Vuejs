<template>
<h2>Two Way Data Binding</h2>
<input type="text" v-model="count"/>
<h2>{{count}}</h2>
</template>

<script>
export default{
    name:"Home",
    data(){
        return{
            count:0
        }
    },

}
</script>
<style>
h1{
    color: orange;
}
</style>