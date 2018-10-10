<template>
    <b-container class="bv-example-row" fluid="">
        <b-row align-v="center">
            <b-col md=12 class="floor text-center">
                {{ title }}
            </b-col>
        </b-row>

        <b-row align-v="center">
            <b-col md="4">
                <div class="image-title"></div>
            </b-col>
            <b-col md="4">
                <div class="image-title"></div>
            </b-col>
            <b-col md="4">
                <div class="image-title"></div>
            </b-col>
        </b-row>

        <b-row align-v="start">
            <b-col md="6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Fuga praesentium quod alias omnis enim commodi ipsum id odit at itaque.</b-col>
            <b-col md="6">Lorem ipsum dolor sit amet consectetur adipisicing elit. Iure modi aperiam suscipit? Officia, eligendi recusandae.</b-col>
        </b-row>
    </b-container>
</template>

<script>
export default {
    name: 'Content',
    props: {
        title: String
    }
}
</script>

<style scoped>
    .floor {
        margin-top: 4%;
        font-size: 2em;
        font-family: monospace;
    }

    .image-title {
        background-position: center;
        background-image: url(https://png.pngtree.com/element_our/md/20180301/md_5a9794da1b10e.png);
        background-repeat: no-repeat;
        background-size: contain;
        min-height: 40vh;
    }
</style>
