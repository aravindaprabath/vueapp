<template>
        <div class="app-wrapper">
            <router-view></router-view>
        </div>
</template>

<script>
</script>


<style lang="scss" >
    :root {
        font-size: 13px;
        @media screen and (min-width: 576px) {
            font-size: 14px;
        }
        @media screen and (min-width: 768px) {
            font-size: 15px;
        }
        @media screen and (min-width: 992px) {
            font-size: 16px;
        }
        @media screen and (min-width: 1200px) {
            font-size: 17px;
        }
    }

    body {
        padding: 0;
        margin: 0;
        box-sizing: border-box;
        font-family: 'Poppins', sans-serif;
        -webkit-font-smoothing: antialiased;
        text-rendering: optimizeLegibility;

    }

    h1 {
        font-size: 3rem;
        letter-spacing: .03em;
        line-height: 1.1em;
        margin: 0 0 .5em;
        font-weight: 600;

    }

    h2 {
        font-size: 2rem;
        letter-spacing: .03em;
        line-height: 1.2em;
        margin: 0 0 .5em;

    }

    h3 {
        font-size: 1.5rem;
        letter-spacing: .03em;
        line-height: 1.2em;
        margin: 0 0 .5em;

    }

    h4 {
        font-size: 1.3rem;
        letter-spacing: .03em;
        line-height: 1.2em;
        margin: 0 0 .5em;
    }



    p {
        font-size: 1.1rem;
        letter-spacing: .03em;
        line-height: 1.6em;
        margin: 0 0 .5em;
        @media screen and (min-width: 576px) {}
        @media screen and (min-width: 768px) {
            font-size: 1rem;
            letter-spacing: .03em;
            line-height: 1.6em;
        }

    }

    img,
    li,
    a {
        font-size: 1rem;
    }

    a {
        text-decoration: none;
        &:hover {
            text-decoration: none;
        }
    }

    .app-wrapper{
        height: 100vh;
        width: 100vw;
        max-height: 100vh;

    }


</style>
