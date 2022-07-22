<template>
    <div>
        <header>
            <div class="container header-wrapper">

                <figure>
                    <img src="../assets/img/dc-logo.png" alt="">
                </figure>
                <nav>
                    <ul class="header-links">
                        <li><a href="">prova</a></li>
                        <li><a href="">prova</a></li>
                        <li><a href="">prova</a></li>
                        <li><a href="">prova</a></li>
                        <li><a class="active" href="">prova</a></li>
                    </ul>
                </nav>
            </div>
        </header>


    </div>
</template>

<script>
export default {
    name: "TheHeader",

};
</script>

<style lang="scss">
@import "../assets/sass/var";

header {
    margin-top: 50px;
    background-color: white;
}

.header-wrapper {
    height: 150px;
    display: flex;
    justify-content: space-between;
    align-items: center;

}

nav .header-links {


    display: flex;
    align-items: center;
    gap: 30px;
    font-size: 1.2rem;
}

.header-links a {
    display: block;
    height: 150px;
    line-height: 150px;

}

.header-links a:hover,
.header-links a.active {

    border-bottom: 4px solid $dc_primary;
    color: $dc_primary;
}
</style>