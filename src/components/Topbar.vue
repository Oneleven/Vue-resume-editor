<template>
    <div id="topbar">
        <div class="logo">logo</div>
        <div class="action" style="margin: 20px 0"> 
            <button>注册</button>
            <button>登入</button>
            <el-button type="success">注册</el-button>
            <el-button type="success">登入</el-button>
        </div>
    </div>
</template>

<style lang="scss">
    #topbar{
        border:1px solid black;
        display:flex;
        justify-content: space-between;
        > .action{
            margin-right: 1rem;
        }
        > .logo{
            margin-left: 1rem;
        }
    }
</style>
