<script>
export default {
    
}
</script>

<template>
    <section class="price section container" id="price">
        <div class="price__container grid">
            <div class="price__card">
                <div class="price__badge">
                    BASIC
                </div>
                <h2 class="section__title">$ 100 USD</h2>
                <p class="price__description">
                    Lorem ipsum dolor sit amet, ametor
                    consectetur adipiscing elit. Et nibh.
                </p>

                <ul class="price__list">
                    <h3 class="subtitle">
                        FEATURES
                    </h3>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Everything included in Basic
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Trading up to $1MM per month
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Windows & macOS App
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Premium Support
                        </p>
                    </li>
                </ul>

                <a href="#" class="button-main">
                    CONTACT US
                </a>
            </div>

            <div class="price__card">
                <div class="price__badge">
                    PRO
                </div>
                <h2 class="section__title">$ 100 USD</h2>
                <p class="price__description">
                    Lorem ipsum dolor sit amet, ametor
                    consectetur adipiscing elit. Et nibh.
                </p>

                <ul class="price__list">
                    <h3 class="subtitle">
                        FEATURES
                    </h3>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Everything included in Basic
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Trading up to $1MM per month
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Windows & macOS App
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Premium Support
                        </p>
                    </li>
                </ul>

                <a href="#" class="button-main">
                    CONTACT US
                </a>
            </div>

            <div class="price__card">
                <div class="price__badge">
                    EXPERT
                </div>
                <h2 class="section__title">$ 100 USD</h2>
                <p class="price__description">
                    Lorem ipsum dolor sit amet, ametor
                    consectetur adipiscing elit. Et nibh.
                </p>

                <ul class="price__list">
                    <h3 class="subtitle">
                        FEATURES
                    </h3>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Everything included in Basic
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Trading up to $1MM per month
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Windows & macOS App
                        </p>
                    </li>
                    <li class="price__item">
                        <p class="price__item-icon">🔵</p>
                        <p class="price__item-description">
                            Premium Support
                        </p>
                    </li>
                </ul>

                <a href="#" class="button-main">
                    CONTACT US
                </a>
            </div>
        </div>
    </section>

    <section class="price__line">

    </section>
</template>

<style scoped>
.price__badge{
    width: 90px;
    text-align: center;
    padding: 9px 18px;
    border-radius: 100px;
    background-color: #0328EE;
}

.price__container{
    row-gap: 2.5rem;
}

.price__card{
    display: grid;
    row-gap: 1rem;
    padding: 40px 25px;
    background: #010D50;
    border-radius: 40px;
}

.price__description{
    margin-bottom: 1rem;
}

.price__list{
    display: grid;
    row-gap: 0.5rem;
}

.price__item{
    display: flex;
    align-items: center;
    column-gap: .5rem;
}

.price__line{
    padding: 50px 0;
}
</style>