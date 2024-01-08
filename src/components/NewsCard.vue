<script>
import { RouterLink } from 'vue-router';
export default {
    
}
</script>

<template>
    <RouterLink to="/about" class="news__card">
        <img src="../assets/img/news-img.png" class="news__img">

        <div class="news__info">
            <span class="news__badge button-main">
                PRODUCTS
            </span>
            <h3 class="subtitle">
                The Basics about Cryptocurrency
            </h3>
            <p class="news__description">
                Lorem ipsum dolor sit ametero irseo,
                consectetur adipiscing elit. Scelerisque
                viverra donec diammeo.
            </p>

            <hr class="news__line">

            <div class="news__profile-box">
                <img src="../assets/img/news-profile-img.svg" class="news__profile-img">

                <h3 class="subtitle">
                    ALEX TURNER <br>
                    <span class="news__subtitle">AUGUST 2,2021</span>
                </h3>
            </div>
        </div>
    </RouterLink>
</template>

<style scoped>
.news__card{
    background: #010D50;
    border-radius: 40px;
}

.news__img{
    width: 100%;
    border-radius: 40px 40px 0 0;
}

.news__badge{
    position: absolute;
    padding: 9px 15px;
    font-weight: var(--font-small);
    margin-top: -60px;
}

.news__info{
    padding: 35px 20px;
    display: grid;
    row-gap: 1.5rem;
}

.news__line{
    height: 1px;
    background: rgba(255, 255, 255, 0.1);
}

.news__profile-box{
    display: flex;
    align-items: center;
    column-gap: 1rem;
}

.news__profile-img{
    border-radius: 50%;
}

.news__subtitle{
    font-size: var(--normal-font-size);
    font-weight: var(--font-small);
}
</style>