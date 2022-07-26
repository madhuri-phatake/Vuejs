<template>
<div>
    <h1>for loop</h1>

    <ul>
        <li v-for="item in technology" :key="item">
        {{item}}
        </li>
    </ul>
    <br/>
    <br/>
    <br/>
    <ul>
        <li v-for="item in user" :key="item.email">
        Name is:{{item.name}} and Email is:{{item.email}}
        </li>
    </ul>

</div>
</template>

<script>
export default{
    name:'gyashgxzvsahxLoop',
    data(){
        return{
        technology:['java','php','node','html'],
        user:[{
            name:"madhuri",
            email:"madhu@gmail.com"
        },
        {
            name:"shubha",
            email:"shubha@gmail.com"
        },
        {
            name:"komal",
            email:"komal@gmail.com"
        } ]
    }
}
}
</script>