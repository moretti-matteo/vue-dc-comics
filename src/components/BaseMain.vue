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


    main{
        background-color: var(--bg-black);
        color:var(--text-white);
        height: 150px;

        .container{
            display: flex;
            align-items: center;
            height: 100%;
        }
    }
</style>