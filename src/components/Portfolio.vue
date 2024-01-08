<script>
export default {
    
}
</script>

<template>
    <section class="portfolio section container" id="portfolio">
        <h2 class="portfolio__title section__title-center">
            Build your crypto portfolio
        </h2>
        <p class="portfolio__description">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br>
            Feugiat nulla suspendisse tortor aene.
        </p>
        <div class="portfolio__container grid">
            <div class="portfolio__data">
                <div class="portfolio__card">
                    <img src="../assets/icons/portfolio-icon-1.svg" alt="" class="portfolio__icon">
                    <h3 class="portfolio__subtitle">
                        SEND & RECEIVE
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet,
                        consectetur adipiscing elit. Feugiat
                        nulla suspendisse tortor aene.
                    </p>
                </div>
                <div class="portfolio__card">
                    <img src="../assets/icons/portfolio-img-2.svg" alt="" class="portfolio__icon">
                    <h3 class="portfolio__subtitle">
                        100% SECURE WALLET
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet,
                        consectetur adipiscing elit. Feugiat
                        nulla suspendisse tortor aene.
                    </p>
                </div>
            </div>

            <div class="portfolio__data">
                <div class="portfolio__card-full">
                    <h3 class="portfolio__subtitle">
                        IOS & ANDROID APP
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet, consectetur adipiscing
                        elit. In amet, morbi non at sed neque.
                    </p>
                    <img src="../assets/img/portfolio-img.png" alt="" class="portfolio__img">
                </div>
            </div>

            <div class="portfolio__data">
                <div class="portfolio__card">
                    <img src="../assets/icons/portfolio-img-3.svg" alt="" class="portfolio__icon">
                    <h3 class="portfolio__subtitle">
                        TRADING CHARTS
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet,
                        consectetur adipiscing elit. Feugiat
                        nulla suspendisse tortor aene.
                    </p>
                </div>
                <div class="portfolio__card">
                    <img src="../assets/icons/portfolio-img-4.svg" alt="" class="portfolio__icon">
                    <h3 class="portfolio__subtitle">
                        REAL TIME TRADING
                    </h3>
                    <p>
                        Lorem ipsum dolor sit amet,
                        consectetur adipiscing elit. Feugiat
                        nulla suspendisse tortor aene.
                    </p>
                </div>
            </div>
        </div>

        <a href="#" class="p__d-btn button-main">
            DOWNLOAD APP
        </a>
    </section>
</template>

<style scoped>
    .portfolio__container{
        row-gap: 2.5rem;
        margin-bottom: 2rem;
    }

    .portfolio__data{
        display: grid;
        row-gap: 2.5rem;
    }

    .portfolio__card{
        padding: 2.5rem 1.5rem;
        display: grid;
        row-gap: 1.5rem;
        background: #010D50;
        border-radius: 40px;
    }

    .portfolio__card-full{
        padding: 2.5rem 1.5rem 0 1.5rem;
        display: grid;
        row-gap: 1.5rem;
        background: #0328EE;
        border-radius: 40px;
    }

    .portfolio__description{
        text-align: center;
        margin-bottom: 3rem;
    }

    .p__d-btn{
        width: 200px;
        margin: 0 auto;
    }
</style>