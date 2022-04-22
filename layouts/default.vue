<template>
    <div>
        <header class="header">
            <div class="header-div">
                <h1 class="header-h1">Sweden Car Blog</h1>
                <nuxt-link class="nuxt-link1" to="/">Home Page</nuxt-link>
                <nuxt-link class="nuxt-link2" to="/about-us">About Us</nuxt-link>
            </div>
        </header>
        <nuxt/>
    </div>  
</template>

<style>
body{
    background-image: url(/pattern.jpg);
    background-size: cover;
}
.header{
    background-color:rgba(0, 0, 0, 0.87);
    height: 35px;
}
.header-div{
    color: white;
    padding: 4px;
    display: flex;
}
.header-h1{
    margin-right: 15px;
    
}
.nuxt-link1{
    text-decoration: underline;
    position: absolute;
    right: 40px;
}
.nuxt-link2{
    text-decoration: underline;
    position: absolute;
    right: 150px;
}
</style>
