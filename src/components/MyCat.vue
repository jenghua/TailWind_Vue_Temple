<template>
    <div>
        <h2>{{ value }}</h2>
        <h2>{{ count }}</h2>
        <button @click="count++">say hello</button>
    </div>


<div class="flex justify-center bg-gray-200">
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">1</div>
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">2</div>
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">3</div>
</div>

<div class="flex justify-between bg-gray-200">
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">1</div>
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">2</div>
  <div class="text-gray-700 text-center bg-gray-400 px-4 py-2 m-2">3</div>
</div>

<button type="button" class="bg-gradient-to-r from-teal-400 to-blue-500 focus:from-pink-500 focus:to-orange-500 text-white font-semibold px-4 py-2 rounded">
  Focus me
</button>
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