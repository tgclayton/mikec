<template>
    <div class="banner">
        <RouterLink to="/" class="logo">
            <img class="logo-img" src="../assets/mikec_transparent_white.png">
        </RouterLink>

        <nav class="nav">
            <!-- <NavItem title="Home" route=""></NavItem> -->
            <NavItem title="About" route="about"></NavItem>
            <NavItem title="Sixty-One SRT" route="sixtyone"></NavItem>
            <NavItem title="SRT Parts/Ordering" route="parts"></NavItem>
            <NavItem title="Contact" route="contact"></NavItem>
        </nav>
    </div>
</template>

<script setup lang="ts">
import { RouterLink } from 'vue-router'
import NavItem from './NavItem.vue'

</script>

<style scoped>

.banner {
    background-color: var(--brand-color);
    border-top: calc((var(--gutter) / 3)) solid black;
    border-bottom: calc((var(--gutter) / 3)) solid black;
    /* border-radius: 5px; */
    max-width: 800px - 1px;
    color: var(--banner-color);
    height: 12vh;
    display:flex;
    flex-direction: row;
    font-size: large;
    justify-content: center;
    align-items: center;
    /* margin: var(--gutter); */

    nav{
        width: 100%
    }
}

.nav{
    max-width: 1050px;
    display:flex;
    flex-direction: row;
    justify-content: space-evenly;
    list-style: none;
    align-items: center;
    
    a {
        color: var(--banner-color);
        text-decoration: none;
    }

    :visited {
        color: var(--banner-color);
    }
    
    .nav-item{
        display: flex;
        list-style: none;
    }
}

.logo {
        margin-left: var(--gutter);
        height:90%;

        .logo-img{
            height: 100%;
        }
}
</style>
