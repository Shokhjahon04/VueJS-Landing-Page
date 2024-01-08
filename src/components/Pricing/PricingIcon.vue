<script>
export default {
    
}
</script>

<template>
    <section class="p-icon section container" id="p-icon">
        <div class="p-icon__container grid">
            <div class="p-icon__data">
                <img src="@/assets/icons/p-icon-img-1.svg" class="p-icon__img">
                <p class="p-icon__description">
                    Send & receive
                </p>
            </div>

            <div class="p-icon__data">
                <img src="@/assets/icons/p-icon-img-2.svg" class="p-icon__img">
                <p class="p-icon__description">
                    Trading Charts
                </p>
            </div>

            <div class="p-icon__data">
                <img src="@/assets/icons/p-icon-img-3.svg" class="p-icon__img">
                <p class="p-icon__description">
                    Wallet
                </p>
            </div>

            <div class="p-icon__data">
                <img src="@/assets/icons/p-icon-img-4.svg" class="p-icon__img">
                <p class="p-icon__description">
                    Real Time Trading
                </p>
            </div>
        </div>
    </section>
</template>

<style scoped>
.p-icon__container{
    row-gap: 2rem;
}

.p-icon__data{
    display: flex;
    flex-direction: row;
    align-items: center;
    column-gap: 1rem;
}
</style>