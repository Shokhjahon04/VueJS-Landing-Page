<script>
export default {
    
}
</script>

<template>
    <section class="footer" id="footer">
        <div class="footer__container container grid">

            <div class="footer__logo-box">
                <img src="../assets/img/footer-logo.png" class="footer__img">
                <div class="footer__social">
                    <a href="#" class="footer__social-icon">
                        <i class="ri-instagram-line"></i>
                    </a>
                    <a href="" class="footer__social-icon">
                        <i class="ri-facebook-circle-line"></i>
                    </a>
                    <a href="" class="footer__social-icon">
                        <i class="ri-linkedin-box-line"></i>
                    </a>
                </div>
            </div>

            <div class="footer__data grid">
                <div class="footer__data-box">
                    <h3 class="subtitle">MENU</h3>
                    <hr class="footer__line">
                    <ul class="footer__list">
                        <div class="footer__col">
                            <li class="footer__item">
                                <a href="#" class="footer__link">HOME</a>
                            </li>
                            <li class="footer__item">
                                <a href="#" class="footer__link">ABOUT</a>
                            </li>
                            <li class="footer__item">
                                <a href="#" class="footer__link">PRICING</a>
                            </li>
                        </div>
                        <div class="footer__col">
                            <li class="footer__item">
                                <a href="#" class="footer__link">TOKENS</a>
                            </li>
                            <li class="footer__item">
                                <a href="#" class="footer__link">BLOG</a>
                            </li>
                            <li class="footer__item">
                                <a href="#" class="footer__link">CONTACT US</a>
                            </li>
                        </div>
                    </ul>
                </div>

                <div class="footer__card">
                    <h3 class="subtitle">DOWNLOAD OUR APPLICATION</h3>
                    <p class="footer__description">
                        Lorem ipsum dolor sit amet, consectetur
                        adipiscing elit. Mauris sed nulla integer 
                    </p>
                    <div class="footer__buttons">
                        <a href="#" class="footer__btn program__button button-main">
                            <i class="ri-apple-fill program-icon"></i>
                            APP STORE
                        </a>
                        <a href="#" class="footer__btn program__button button-main">
                            <i class="ri-google-play-fill program-icon"></i>
                            PLAY STORE
                        </a>
                    </div>
                </div>
            </div>

            <hr class="footer__line">

            <p class="footer__description">
                All rights reserved! <br>
                Website created by HUSANOV SHOHJAHON
            </p>
        </div>
    </section>
</template>

<style scoped>
.footer{
    padding: 5rem 0;
    background: #010D50;
}

.footer__container{
    row-gap: 2rem;
}

.footer__logo-box{
    display: flex;
    flex-direction: column;
    align-items: center;
    row-gap: 1.5rem;
}

.footer__social{
    display: flex;
    align-items: center;
    column-gap: 1rem;
}

.footer__social-icon{
    padding: 8px 12px;
    border-radius: 50%;
    background: rgba(255, 255, 255, 0.5);
    color: #FFFFFF;
    font-size: 1.5rem;
}

.footer__data{
    row-gap: 3rem;
}

.footer__data-box{
    display: grid;
    row-gap: .5rem;
}

.footer__line{
    width: 100%;
    height: 1px;
    background: rgba(255, 255, 255, 0.3);
}

.footer__list{
    display: flex;
    flex-direction: row;
    align-items: center;
    column-gap: 6rem;
}

.footer__item{
    margin-bottom: .5rem;
}

.footer__link{
    color: #FFFFFF;
}

.footer__card{
    padding: 40px 30px;
    display: grid;
    row-gap: 1.5rem;
    background: rgba(255, 255, 255, 0.1);
    border-radius: 40px;
}

.footer__buttons{
    display: flex;
    flex-direction: column;
    row-gap: 1rem;
}

.footer__btn{
    margin: 0;
}
</style>