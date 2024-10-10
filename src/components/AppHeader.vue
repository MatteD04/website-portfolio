<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="ms-header">
        <ul class="nav ms-navbar nav-underline">
            <li class="nav-item">
                <router-link class="nav-link link-dark" :to="{name: 'home'}">Home</router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link link-dark" :to="{name: 'about'}">About</router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link link-dark" :to="{name: 'projects'}">Projects</router-link>
            </li>
            <li class="nav-item">
                <router-link class="nav-link link-dark" :to="{name: 'contacts'}">Contacts</router-link>
            </li>
        </ul>
    </div>
</template>

<style>
.ms-header{
    background-color: rgba(60, 0, 255, 0.616);
}
.ms-navbar{
    justify-content: center;
    li{
        font-size: 20px;
        font-weight: 500;
        margin: 0px 20px;
        a{
            color: black;
        }
        a:hover{
            color: white
        }
    }
}
</style>