<script>
export default {
    
}
</script>

<template>
    <section class="home" id="home">
        <div class="home__container grid container">
            <div class="home__data">
                <h1 class="home__title">
                    Buy, trade and hold
                    350+ cryptocurrencies
                </h1>
                <p class="home__description">
                    Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit. Feugiat nulla suspendisse
                    tortor aenean dis placerat.
                </p>
                <div class="home__button-box">
                    <a href="#" class="button-main">
                        DOWNLOAD APP
                    </a>
                    <RouterLink to="/pricing" class="button-dark">
                        VIEW PRICING
                    </RouterLink>
                </div>
            </div>

            <img src="../assets/img/home-img.png" alt="" class="home__img">
            <!-- home img mobile -->
            <img src="../assets/img/home-img-mobile.png" alt="" class="home__img-mobile">
        </div>
    </section>
</template>

<style scoped>
/*=============== HOME ===============*/
.home{
    padding: 2.5rem 0;
}

.home__container{
    row-gap: 2.5rem;
}

.home__title{
    font-size: var(--big-font-size);
    font-weight: var(--font-bold);
    margin-bottom: 2rem;
}

.home__description{
    margin-bottom: 2rem;
}

.home__button-box{
    display: grid;
    row-gap: 1rem;
}

.home__img{
    display: none;
}

.home__img-mobile{
    justify-self: center;
    width: 80%;
}
</style>