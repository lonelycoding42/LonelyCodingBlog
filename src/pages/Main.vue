<template>
    <div class="main">
        <UserInfo />
        <MyBloglists />
    </div>  
</template>

<script>
import UserInfo from "../components/UserInfo.vue";
import MyBloglists from "../components/MyBloglists.vue";
export default{
    components:{
        UserInfo,
        MyBloglists 
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