<template>
    <div>
        <h2>{{ value }}</h2>
        <h2>{{ count }}</h2>
        <button @click="count++">say hello</button>
    </div>
</template>
<script>
export default {
    props:{
        value:String
    },
    data:function(){
        return{
            count: 0
        };
    }
}
</script>