<template>
    <div class="main">
        <h3>This is main</h3> 
        <UserInfo />
    </div>
</template>

<script>
import UserInfo from "./UserInfo.vue";
export default{
    components:{
       UserInfo
    }
}
</script>

<style scoped>
.main{
    float: left;
    width: 100%;
    height: 700px;
    border: 5px solid #999;
    box-sizing: border-box;
}
</style>