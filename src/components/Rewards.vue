<script>
export default {
    
}
</script>

<template>
    <section class="rewards container" id="rewards">
        <div class="rewards__container grid">
            <img src="../assets/img/rewords-img-1.png" class="rewards__img">

            <div class="rewards__data">
                <h2 class="section__title">
                    Earn daily rewards on
                    your idle tokens
                </h2>
                <p class="rewards__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Feugiat nulla suspendisse tortor aene.
                </p>
                <ul class="icon__list">
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-1.svg" class="icon__img">
                        <h3 class="subtitle">
                            Lowest fees in market
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-2.svg" class="icon__img">
                        <h3 class="subtitle">
                            Fast and secure transactions
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-3.svg" class="icon__img">
                        <h3 class="subtitle">
                            Fast and secure transactions
                        </h3>
                    </li>
                </ul>
            </div>
        </div>

        <div class="rewards__container grid">
            <div class="rewards__data">
                <h2 class="section__title">
                    Earn daily rewards on
                    your idle tokens
                </h2>
                <p class="rewards__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Feugiat nulla suspendisse tortor aene.
                </p>
                <ul class="icon__list">
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-4.svg" class="icon__img">
                        <h3 class="subtitle">
                            100% Private data
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-5.svg" class="icon__img">
                        <h3 class="subtitle">
                            99.99% Uptime guarantee
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/rewards-icon-6.svg" class="icon__img">
                        <h3 class="subtitle">
                            24/7 Dedicated support
                        </h3>
                    </li>
                </ul>
            </div>

            <img src="../assets/img/home-img-mobile.png" class="rewards__img r__img">
        </div>
    </section>
</template>

<style scoped>
.rewards{
    padding: 5.5rem 0 7rem;
    display: grid;
    row-gap: 6.5rem;
}

.rewards__container{
    row-gap: 2.5rem;
}

.rewards__description{
    margin-bottom: 2.5rem;
}

.img__order-1{
    order: 1;
}

.r__img{
    width: 100%;
}
</style>