<!-- <template>
<h1 v-if="show">If Else Condiotion</h1>
<h1 v-else> Else Condiotion</h1>

<button v-on:click="show=!show">Toogle</button>
</template>

<script>
export default{
    name:"ifElse",
    data(){
        return{
            show:true
        }
    }
}
</script>

<style scoped>
h1{
    color: orange;
}
</style> -->

<template>
<div>
<h1>{{even}}</h1>
<input type="text" v-model="even"/>
<button v-on:click="EvenNum()" type="button" >Button</button>

</div>
</template>

<script>
export default{
    data(){
        return{
        even:0,
        odd:0,
        }
    },
    methods:{
        EvenNum(){
            if(this.even%2==0){
                alert(this.even+' is even number.');
            }else{
                alert(this.even+" is odd number");
            }
        }
    }
}
</script>