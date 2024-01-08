<script>
import AboutHome from '../components/About/AboutHome.vue';
import AboutDrive from '../components/About/AboutDrive.vue';
import AboutMission from '../components/About/AboutMission.vue';
import Team from "../components/About/Team.vue";
import Investors from "../components/Investors.vue";

export default {
    components: {
        AboutHome,
        AboutDrive,
        AboutMission,
        Team,
        Investors,
    }
}
</script>

<template>
    <AboutHome />
    <AboutDrive />
    <AboutMission />
    <Team />
    <Investors />

    <div class="a-investors"></div>
</template>

<style scoped>
.a-investors{
    margin-bottom: 8rem;
}
</style>