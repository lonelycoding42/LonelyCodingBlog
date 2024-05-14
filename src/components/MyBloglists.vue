<!-- 博客文章的简略展示,按照从高到低的位置 -->
<template>
    <ul>
        <div class="List" v-for="(item, index) in data" :key="item.id">
            {{ index }} - {{ item.name }} - {{ item.age }}
        </div>
    </ul>
</template>
   
<script setup>
  import { reactive } from "vue";
  let data = reactive([
    { id: 1, name: "张三", age: 21 },
    { id: 2, name: "李四", age: 18 },
    { id: 3, name: "王五", age: 26 },
    { id: 4, name: "张三", age: 21 },
    { id: 5, name: "张三", age: 21 },
    { id: 6, name: "张三", age: 21 },
  ]);


</script>

<style>
.List{
    background-color:aquamarine;
    float:inline-start;
    width: 80%;
    height: 150px;
    border: 5px solid #999;
    box-sizing: border-box;
}
  
</style>