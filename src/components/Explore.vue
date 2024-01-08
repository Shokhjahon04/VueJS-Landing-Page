<script>
export default {
    
}
</script>

<template>
    <section class="explore" id="explore">
        <div class="explore__container grid container">
            <div class="explore__data">
                <div class="section__title">
                    Explore endless possibilities
                    with FinanceFlow
                </div>
                <p class="explore__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Feugiat nulla suspendisse tortor aene.
                </p>
                <a href="#" class="explore__button button-white">
                    DOWNLOAD APP
                </a>
            </div>

            <img src="../assets/img/explore-img.png" class="explore__img">
        </div>
    </section>
</template>

<style scoped>
    .explore{
        padding: 4rem 0 0 0;
        background-color: var(--blue-color);
    }

    .explore__container{
        row-gap: 2.5rem;
    }

    .explore__description{
        margin-bottom: 2.5rem;
    }

    .explore__button{
        margin-bottom: 4rem;
    }
</style>