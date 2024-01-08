<script>
export default {
    
}
</script>

<template>
    <section class="start section container" id="start">
        <div class="start__container grid">
            <div class="start__data">
                <h2 class="section__title">
                    Get started today
                </h2>
                <p class="start__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Feugiat nulla suspendisse tortor aene.
                </p>
                <ul class="icon__list">
                    <li class="icon__item">
                        <img src="../assets/icons/start-icon-1.svg" class="icon__img">
                        <h3 class="subtitle">
                            Download app
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/start-icon-2.svg" class="icon__img">
                        <h3 class="subtitle">
                            Create a free account
                        </h3>
                    </li>
                    <li class="icon__item">
                        <img src="../assets/icons/start-icon-3.svg" class="icon__img">
                        <h3 class="subtitle">
                            Start trading
                        </h3>
                    </li>
                </ul>
            </div>

            <div class="start__video">
                <!-- video elements -->
            </div>
        </div>
    </section>
</template>

<style scoped>
.start__container{
    row-gap: 2.5rem;
}

.start__description{
    margin-bottom: 2.5rem;
}

.start__video{
    width: 100%;
    height: 400px;
    background: #010D50;
    border-radius: 40px;
}
</style>