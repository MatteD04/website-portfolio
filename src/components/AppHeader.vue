<script>
export default {
    name: 'AppHeader'
}
</script>

<template>
    <div class="ms-header">
        <ul class="nav ms-navbar">
            <li class="nav-item">
                <a class="nav-link" href="#">Home</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">About</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Projects</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Contacts</a>
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