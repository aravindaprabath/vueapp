<template>
    <div>
        <h1>login layout</h1>
        <login-component></login-component>
    </div>

</template>

<script>
    import LoginComp from "src/components/login/login-component";


    export default {
        components: {
            "login-component": LoginComp
        },
    }

</script>