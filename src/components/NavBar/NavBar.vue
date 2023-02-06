<script setup lang="ts">

</script>

<template>
    <offers />
    <div flex justify-between p3 h13 bg="#101010" text="#e8e8e8" dark:bg="#202020">
        <div md:flex hidden>
            <div mx2>
                <router-link to="/shop">
                    Shop
                </router-link>
            </div>
            <div mx2>
                <router-link to="/about">
                    About
                </router-link>
            </div>
            <div mx2>
                <router-link to="/blog">
                    Blog
                </router-link>
            </div>
        </div>
        
        <div
            mx2 flex
            style="font-family: 'Zen Dots', cursive;">
            <div md:hidden mx2 my="2px" text="5">
                <div i-carbon-menu />
            </div>
            <router-link to="/">
                <h1>EBI</h1>
            </router-link>
        </div>
        <div flex>
            <div mx2>
                <router-link to="/cart">
                    Cart
                </router-link>
            </div>
            <div mx2>
                <router-link to="/login">
                    Login/Register
                </router-link>
            </div>
        </div>
    </div>
</template>

