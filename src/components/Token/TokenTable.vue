<script>
export default {
    
}
</script>

<template>
    <section class="token container" id="token">
        <ul class="token__container grid">
            <li class="token__item token__subtitles">
                <h3 class="subtitle">1. NAME</h3>
                <h3 class="subtitle">2. DESCRIPTION</h3>
                <h3 class="subtitle">3. MARKET CAP</h3>
                <h3 class="subtitle">4. VOLUME</h3>
                <h3 class="subtitle">5. WEBSITE</h3>
            </li>
            <hr class="token__line">

            <li class="token__item">
                <div class="token-box">
                    <img src="@/assets/icons/token-img-1.svg" class="token__img">
                    <h3 class="subtitle">Bitcoin</h3>
                    <p class="token__badge">BTC</p>
                </div>
                <p class="token__description">DESCRIPTION</p>
                <h3 class="subtitle">$252,844,036,453 USD</h3>
                <h3 class="subtitle">$30,504,879,301 USD</h3>
                <a href="#" class="token__link">Visit Website</a>
            </li>
            <hr class="token__line">

            <li class="token__item">
                <div class="token-box">
                    <img src="@/assets/icons/token-img-2.svg" class="token__img">
                    <h3 class="subtitle">Ethereum</h3>
                    <p class="token__badge">ETH</p>
                </div>
                <p class="token__description">DESCRIPTION</p>
                <h3 class="subtitle">$252,844,036,453 USD</h3>
                <h3 class="subtitle">$30,504,879,301 USD</h3>
                <a href="#" class="token__link">Visit Website</a>
            </li>
            <hr class="token__line">

            <li class="token__item">
                <div class="token-box">
                    <img src="@/assets/icons/token-img-3.svg" class="token__img">
                    <h3 class="subtitle">Litecoin</h3>
                    <p class="token__badge">LTC</p>
                </div>
                <p class="token__description">DESCRIPTION</p>
                <h3 class="subtitle">$252,844,036,453 USD</h3>
                <h3 class="subtitle">$30,504,879,301 USD</h3>
                <a href="#" class="token__link">Visit Website</a>
            </li>
            <hr class="token__line">

            <li class="token__item">
                <div class="token-box">
                    <img src="@/assets/icons/token-img-4.svg" class="token__img">
                    <h3 class="subtitle">TRON</h3>
                    <p class="token__badge">TRX</p>
                </div>
                <p class="token__description">DESCRIPTION</p>
                <h3 class="subtitle">$252,844,036,453 USD</h3>
                <h3 class="subtitle">$30,504,879,301 USD</h3>
                <a href="#" class="token__link">Visit Website</a>
            </li>
            <hr class="token__line">
        </ul>
    </section>
</template>

<style scoped>
.token{
    padding: 2rem 0 8.5rem;
}

.token__container{
    row-gap: 40px;
}

.token__item{
    display: flex;
    flex-direction: column;
    row-gap: 2rem;
}

.token__line{
    width: 100%;
    height: 1px;
    background: #010D50;
}

.token-box{
    display: flex;
    align-items: center;
    column-gap: 1rem;
}

.token__badge{
    width: 50px;
    border-radius: 100px;
    background-color: #010D50;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 3px 5px;
}

.token__link{
    text-decoration-line: underline;
}
</style>