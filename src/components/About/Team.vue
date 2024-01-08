<script>
export default {
    
}
</script>

<template>
    <section class="team section container" id="team">
        <h2 class="section__title">
            Our Team
        </h2>
        <div class="team__container grid">
            <div class="team__card">
                <img src="@/assets/img/about-team-img-1.png" class="team__img">
                <h3 class="subtitle">JOHN CARTER</h3>
                <p class="team__deascription">
                    CEO & CO-FOUNDER
                </p>
            </div>

            <div class="team__card">
                <img src="@/assets/img/about-team-img-2.png" class="team__img">
                <h3 class="subtitle">SOPHIE MOORE</h3>
                <p class="team__deascription">
                    COMMUNITY LEAD
                </p>
            </div>

            <div class="team__card">
                <img src="@/assets/img/about-team-img-3.png" class="team__img">
                <h3 class="subtitle">ALEX TURNER</h3>
                <p class="team__deascription">
                    OPERATIONS
                </p>
            </div>
        </div>
    </section>
</template>

<style scoped>
.team__container{
    row-gap: 1.5rem;
}

.team__card{
    background: #010D50;
    border-radius: 40px;
    padding: 20px;
    display: grid;
    row-gap: .5rem;
}

.team__img{
    width: 100%;
    margin-bottom: 1.5rem;
}
</style>