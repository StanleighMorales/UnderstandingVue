<template>
    <div class="nav">
        <div class="logo">
            <div class="img"></div>
            <div class="logo-title">VuePractice</div>
        </div>
        <div class="a-links">
            <ul>Home</ul>
            <ul>About</ul>
            <ul>Contact</ul>
            <div class="profile">
                <img src="" alt="P">
            </div>
        </div>
        
    </div>
</template>
<style scoped>
    *{
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        
    }
    .nav{
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 0px 35px 0px 35px;
        height: 60px;
        background-color: aqua;
    }
    .a-links {
        display: flex;
        align-items: center;
        gap: 50px;
        height: auto;
        width: auto;
        
    }
    @media (max-width: 500px ) {
        .a-links{
            color: rgb(255, 0, 0);
        }
        
    }


</style>