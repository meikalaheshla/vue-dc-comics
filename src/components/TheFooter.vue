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
                <div class="container bot-footer-wrapper">
                    <div class="bot-footer-buttons">

                        <button id="sign-up-button">SIGN-UP NOW</button>
                    </div>
                    <div class="social-links">
                        <a id="follow-us-link" href="#">FOLOOW US</a>
                        <a href="#"><img src="../assets/img/footer-facebook.png" alt="facebook"></a>
                        <a href="#"><img src="../assets/img/footer-twitter.png" alt="twitter"></a>
                        <a href="#"><img src="../assets/img/footer-youtube.png" alt="youtube"></a>
                        <a href="#"><img src="../assets/img/footer-pinterest.png" alt="pinterest"></a>
                        <a href="#"><img src="../assets/img/footer-periscope.png" alt="periscope"></a>


                    </div>
                </div>
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
    padding: 40px 0;
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


// TOP FOOTER RIGHT SIDE

#top-footer figure {
    height: 100%;
}

#top-footer img {
    object-position: 0 -95px;

}


// BOTTOM FOOTER

#bottom-footer {
    // to remove
    height: 100px;

    background-color: $bot_footer_bg_color;
    padding: 20px;
}

// BOTTOM FOOTER LAYOUT
#bottom-footer .bot-footer-wrapper {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

// BOTTOM FOOTER BUTTONS SECTION

#bottom-footer #sign-up-button {
    padding: 12px 15px;
    background-color: inherit;
    color: $main_txt_color;
    font-weight: 400;
    font-size: 1.1rem;
    border: 2px solid $dc_primary;
}

// BOTTOM FOOTER SOCIAL LINK SECTION
#bottom-footer .social-links {
    display: flex;
    gap: 20px;
    align-items: center;
}

#bottom-footer #follow-us-link {
    color: $dc_primary ;
    font-weight: bold;
    font-size: 1.2rem;
}
</style>