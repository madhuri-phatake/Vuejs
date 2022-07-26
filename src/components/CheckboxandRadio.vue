<template>
<h2>Technology</h2>

<label for="java">Java</label>
<input type="checkbox" value="java" v-model="technology" id="java"/>

<label for="php">Php</label>
<input type="checkbox" value="php" v-model="technology" id="php"/>

<label for="node">Node</label>
<input type="checkbox" value="node" v-model="technology" id="node"/>


<h4>Selected Radio Button</h4>
<label for="student">student</label>
<input type="radio" value="student" v-model="who" id="student"/>

<label for="developer">Developer</label>
<input type="radio" value="developer" v-model="who" id="developer"/>

<h2>Selected Technology:{{technology}}</h2>
<h2>Who I am:{{who}}</h2>

</template>




<script>
export default{
    name:"Checkbox",
    data(){
        return {
            technology:[],
            who:null
        }
    }
}
</script>