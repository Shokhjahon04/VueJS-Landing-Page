<script>
export default {
    
}
</script>

<template>
    <section class="investors section container" id="investors">
        <p class="investors__description">
            Finance flow has been featured on
        </p>
        <div class="investors__container grid">
            <img src="../assets/img/investors-img-1.png" class="investors__data">
            <img src="../assets/img/investors-img-2.png" class="investors__data">
            <img src="../assets/img/investors-img-3.png" class="investors__data">
            <img src="../assets/img/investors-img-4.png" class="investors__data">
            <img src="../assets/img/investors-img-5.png" class="investors__data">
        </div>
    </section>
</template>

<style scoped>
    .investors__description{
        text-align: center;
        margin-bottom: 2.5rem;
    }

    .investors__container{
        grid-template-columns: repeat(2, 1fr);
        justify-content: center;
        align-items: center;
        gap: 2rem;
    }

    .investors__data{
        width: 100%;
    }
</style>