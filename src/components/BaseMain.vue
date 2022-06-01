<template>
    <main>
        <div class="container">
            <h2>--> Content goes here &lt;--</h2>
        </div>
    </main>
</template>

<script>
export default {
    name: 'BaseMain'
}
</script>

<style lang="scss">
@import "../assets/style/variables.css";
@import "../assets/style/global.css";

    main{
        border:1px solid orange;
        background-color: var(--bg-black);
        color:white;
        height: 150px;

        .container{
            display: flex;
            align-items: center;
            height: 100%;
        }
    }
</style>