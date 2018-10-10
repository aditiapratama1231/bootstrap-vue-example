<template>
<!-- <body> -->
    <div class="header">
        <div class="transbox"></div>
    </div>
<!-- </body> -->
</template>


<script>
export default {
    name: 'Header',
    props: {
        name: String,
        about: String
    }
}
</script>

<style scoped>
    .header {
        width: 100%;
        color:white;
        background-image: url(https://pixabay.com/get/ec30b1092fe91c66d15a4600e0454496fe76e7d610b0144695f7c8/evening-55067.png);
        background-repeat: no-repeat;
        background-size: cover;
        min-height: 65vh;
        /* opacity: 0.7; */
        /* background-color: lightgrey; */
    }

    .transbox {
        background-color: lightcoral;
        opacity: 0.6;
    }
</style>
