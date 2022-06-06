<template>
    <main>
        <SectionHero></SectionHero>
        <div class="container">
            <SectionCards>

            </SectionCards>
        </div>
    </main>
</template>

<script>
import SectionHero from '../sectionHero/SectionHero.vue';
import SectionCards from '../sectionCards/SectionCards.vue';
export default {
    name: 'BaseMain',
    components: {
    SectionHero,
    SectionCards
}

}
</script>

<style lang="scss">



main {
    background-color: var(--bg-black);
    color: var(--text-white);

    .container {
        display: flex;
        align-items: center;
        height: 100%;
    }
}
</style>