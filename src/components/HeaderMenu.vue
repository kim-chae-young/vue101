<template>
    <div>
        <header id="header" >
            <div class="site"><router-link to="/site">Site</router-link></div>
            <div class="logo"><router-link to="/">chaeyoung's portfolio</router-link></div>
            <nav class="nav">
                <ul>
                    <li><router-link to="/about">About</router-link></li>
                    <li><router-link to="/reference">Reference</router-link></li>
                    <li><router-link to="/script">Script</router-link></li>
                    <li><router-link to="/ani">Animation</router-link></li>
                    <li><router-link to="/contact">Contact</router-link></li>
                </ul>
            </nav>
        </header>
    <router-view>
</template>
