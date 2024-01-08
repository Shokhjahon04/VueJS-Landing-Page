<script>
export default {
    
}
</script>

<template>
    <section class="program container" id="program">
        <div class="program__title-box">
            <h2 class="program__title section__title">
                Download our app
            </h2>
            <p class="program__description">
                Lorem ipsum dolor sit amet, consectetur adipiscing <br>
                elit. Sit non neque orci amet, amet .
            </p>
        </div>

        <div class="program__container grid">
            <div class="program__data">
                <h3 class="section__title">
                    Download for iOS
                </h3>
                <p class="program__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing
                    elit. Mauris sed nulla integer in pellentesque tortor
                    semper elementum. Felis.
                </p>
                <a href="#" class="program__button button-main">
                    <i class="ri-apple-fill program-icon"></i>
                    APP STORE
                </a>

                <img src="../assets/img/program-iphone-img.png" class="program__img">
            </div>

            <div class="program__data">
                <h3 class="section__title">
                    Download for Android
                </h3>
                <p class="program__description">
                    Lorem ipsum dolor sit amet, consectetur adipiscing
                    elit. Mauris sed nulla integer in pellentesque tortor
                    semper elementum. Felis.
                </p>
                <a href="#" class="program__button button-main">
                    <i class="ri-google-play-fill program-icon"></i>
                    PLAY STORE
                </a>

                <img src="../assets/img/program-android-img.png" class="program__img">
            </div>
        </div>
    </section>
</template>

<style scoped>
.program{
    padding: 6.5rem 0 5rem;
}

.program__title-box{
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    margin-bottom: 3rem;
}

.program__container{
    row-gap: 1.5rem;
}

.program__data{
    padding: 35px 35px 0 35px;
    background: #010D50;
    border-radius: 40px;
}
</style>