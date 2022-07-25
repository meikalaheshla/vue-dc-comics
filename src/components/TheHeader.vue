<template>
    <div>
        <header>
            <div class="container header-wrapper">

                <figure>
                    <img class="logo" src="../assets/img/dc-logo.png" alt="logo">
                </figure>
                <nav>
                    <ul class="header-links">
                        <li v-for="link in links" :key="link.id">
                            <a :class="{ 'active': link.current }" :href="link.url">
                                {{ link.text }}</a>
                        </li>
                    </ul>
                </nav>
            </div>
        </header>


    </div>
</template>

<script>
export default {
    name: "TheHeader",
    data() {
        return {
            links: [
                {
                    text: 'Characters',
                    url: '#',
                    current: false,
                    id: 1,
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: true,
                    id: 2,
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false,
                    id: 3,
                },
                {
                    text: 'TV',
                    url: '#',
                    current: false,
                    id: 4,
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false,
                    id: 5,
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false,
                    id: 6,
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false,
                    id: 7
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false,
                    id: 8,
                },
                {
                    text: 'News',
                    url: '#',
                    current: false,
                    id: 9,
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false,
                    id: 10,
                },
            ],


        }
    }

};
</script>

<style lang="scss" scoped>
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