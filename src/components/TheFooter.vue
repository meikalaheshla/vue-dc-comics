<template>
    <div>
        <footer>
            <section id="top-footer">
                <div class="row container">
                    <div class="col footer-links">
                        <div class="links-list-box">
                            <h3>DC COMICS</h3>
                            <ul>
                                <li><a href="#">characters</a></li>
                                <li><a href="#">Comics</a></li>
                                <li><a href="#">Movies</a></li>
                                <li><a href="#">TV</a></li>
                                <li><a href="#">Games</a></li>
                                <li><a href="#">Videos</a></li>
                                <li><a href="#">News</a></li>
                            </ul>
                            <h3>SHOP</h3>
                            <ul>
                                <li><a href="#">Shop DC</a></li>
                                <li><a href="#">Shop DC collectibles</a></li>
                            </ul>

                        </div>
                        <div class="links-list-box">
                            <h3>DC</h3>
                            <ul>
                                <li><a href="#">Terns Of Use</a></li>
                                <li><a href="#">Privacy policy(New)</a></li>
                                <li><a href="#">Ad choices</a></li>
                                <li><a href="#">Advertising</a></li>
                                <li><a href="#">Jobs</a></li>
                                <li><a href="#">Subscriptions</a></li>
                                <li><a href="#">Talent Workshops</a></li>
                                <li><a href="#">CPSC Certificates</a></li>
                                <li><a href="#">Ratings</a></li>
                                <li><a href="#">Shop Help</a></li>
                                <li><a href="#">Contact Us</a></li>
                            </ul>
                        </div>
                        <div class="links-list-box">
                            <h3>SITES</h3>
                            <ul>
                                <li><a href="#">DC</a></li>
                                <li><a href="#">MAD Magazine</a></li>
                                <li><a href="#">Dc Kids</a></li>
                                <li><a href="#">Dc Universe</a></li>
                                <li><a href="#">Dc Power Visa</a></li>
                            </ul>
                        </div>
                    </div>
                    <div class="col">
                        <figure><img src="../assets/img/dc-logo-bg.png" alt=""></figure>
                    </div>
                </div>

            </section>
            <section id="bottom-footer">

            </section>
        </footer>
    </div>
</template>
<script>
export default {
    name: "TheFooter"
}
</script>
<style lang="scss">
@import "../assets/sass/var";



// TOP FOOTER


#top-footer {
    height: 400px;
    background-image: url(../assets/img/footer-bg.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    overflow: hidden;
    color: $main_txt_color;
}

// TOP FOOTER LAYOUT

#top-footer .row {
    display: flex;
    height: 100%;

}


#top-footer .col {
    width: calc(100% / 2);
}

// TOP FOOTER LEFT SIDE

#top-footer .footer-links {
    display: flex;
    padding: 20px 0;
    gap: 20px;

}

#top-footer h3 {
    margin-bottom: 20px;
}

#top-footer ul {
    margin-bottom: 20px;

}

#top-footer a {
    color: $footer_link_color;
    font-size: 0.8rem;
}

#top-footer figure {
    height: 100%;
}

#top-footer img {
    object-position: 0 -95px;

}

#bottom-footer {
    // to remove
    height: 100px;

    background-color: $bot_footer_bg_color;
    padding: 20px;
}
</style>