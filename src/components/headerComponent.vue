<template>
    <div class="container py-3 d-flex justify-content-between align-items-center ovverflow-hidden">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="logo">
        </div>
        <nav>
            <ul class="d-flex gap-3">
                <li>
                    <a href="#" class="text-uppercase fw-bold">Characters</a>
                </li>
                <li>
                    <a href="#" class="active text-uppercase fw-bold">Comics</a>
                </li>   
                <li>
                    <a href="#" class="text-uppercase fw-bold">Movies</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Tv</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Games</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Collectibles</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Videos</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Fans</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">News</a>
                </li>
                <li>
                    <a href="#" class="text-uppercase fw-bold">Shop</a>
                </li>
            </ul>
        </nav>
    </div>
</template>

<script>
export default {
    name: 'headerComponent'
}
</script>

<style lang="scss">
.logo{
    width: 100%;
}

.logo img{
    width: 80px;
}

nav a{
    text-decoration: none;
    color: #71776e;
}

nav ul li{
    list-style: none;
    padding: 0;
    margin: 0;
}

.active{
    text-underline-offset: 54px;
    text-decoration: underline 6px #0282f9;
    color: #0282f9;
}

nav ul a:hover{
    color: #0282f9;
}



</style>

