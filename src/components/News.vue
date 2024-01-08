<script>
import { RouterLink } from "vue-router";
import NewsCard from "../components/NewsCard.vue";

export default {
    components: {
        NewsCard,
    }
}
</script>

<template>
    <section class="news section container" id="news">
        <div class="news__title-box">
            <h2 class="news__title section__title">
                Browse our latest news
            </h2>
            <p class="news__description">
                Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                elit. Sit non neque orci amet, amet .
            </p>
        </div>

        <div class="news__container grid">
            <NewsCard />
            <NewsCard />
            <NewsCard />
        </div>

        <RouterLink to="/about" class="news__button button-dark">
            VIEW ALL ARTICLES
        </RouterLink>
    </section>
</template>

<style scoped>
.news__title-box{
    width: 100%;
    display: flex;
    flex-direction: column;
    margin-bottom: 3rem;
}

.news__container{
    row-gap: 2rem;
}

.news__button{
    max-width: 250px;
    margin: 2.5rem auto 0 auto;
}
</style>