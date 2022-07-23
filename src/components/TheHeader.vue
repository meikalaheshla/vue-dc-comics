<template>
    <div>
        <header>
            <div class="container header-wrapper">

                <figure>
                    <img class="logo" src="../assets/img/dc-logo.png" alt="logo">
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
    margin-top: 41px;
    background-color: white;
}

.header-wrapper {
    height: 120px;
    display: flex;
    justify-content: space-between;
    align-items: center;

}

.header-wrapper .logo {
    height: 80px;
}

nav .header-links {


    display: flex;
    align-items: center;
    gap: 30px;
    font-size: 1.1rem;
}

.header-links a {
    display: block;
    height: 120px;
    line-height: 120px;

}

.header-links a:hover,
.header-links a.active {

    border-bottom: 4px solid $dc_primary;
    color: $dc_primary;
}
</style>