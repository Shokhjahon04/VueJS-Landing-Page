<script>
export default {
    
}
</script>

<template>
    <section class="drive section container" id="drive">
        <!-- program title box -->
        <div class="drive__title-box program__title-box">
            <h2 class="drive__title section__title">
                What drives Finance Flow?
            </h2>
            <p class="program__description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br>
                Feugiat nulla suspendisse tortor aene.
            </p>
        </div>

        <div class="drive__container grid">
            <div class="drive__card grid">
                <img src="@/assets/icons/drive-icon-1.svg" class="drive__icon">
                <h3 class="subtitle">OPEN SOURCE</h3>
                <p class="drive__desc">
                    Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit. Et nibh urna in proin dui purus
                    bibendum cras. Morbi cursus nunc.
                </p>
            </div>
            <div class="drive__card grid">
                <img src="@/assets/icons/drive-icon-2.svg" class="drive__icon">
                <h3 class="subtitle">WORLDWIDE</h3>
                <p class="drive__desc">
                    Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit. Et nibh urna in proin dui purus
                    bibendum cras. Morbi cursus nunc.
                </p>
            </div>
            <div class="drive__card grid">
                <img src="@/assets/icons/drive-icon-3.svg" class="drive__icon">
                <h3 class="subtitle">TRANSPARENT</h3>
                <p class="drive__desc">
                    Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit. Et nibh urna in proin dui purus
                    bibendum cras. Morbi cursus nunc.
                </p>
            </div>
            <div class="drive__card grid">
                <img src="@/assets/icons/drive-icon-4.svg" class="drive__icon">
                <h3 class="subtitle">COMMUNITY DRIVEN</h3>
                <p class="drive__desc">
                    Lorem ipsum dolor sit amet, consectetur
                    adipiscing elit. Et nibh urna in proin dui purus
                    bibendum cras. Morbi cursus nunc.
                </p>
            </div>
        </div>
    </section>
</template>

<style scoped>
.drive__title-box{
    margin-bottom: 2rem;
}

.drive__container{
    row-gap: 1.5rem;
}

.drive__card{
    row-gap: 1.5rem;
    padding: 58px 32px;
    background: #010D50;
    border-radius: 40px;
}
</style>