<template>
    <div class="login">
        登录
        <div class="loginContent">
            
        </div>
    </div>
</template>
<script>
export default {
    data () {
        return {
            input: ''
        }
    }
}
</script>
<style lang="scss" scoped>
.login{
    width: 100%;
    height: 100vh;
    background-color: #344a5f;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    .loginContent{
        width: 50%;
        min-height: 200px;
        background-color: #ffffff;
        border-radius: 5px;
    }
}
</style>
