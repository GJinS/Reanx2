<template>
        <p class = "text-center font-mono text-amber-900 bg-orange-100 hover:bg-yellow-50">
        <br>
        <div class = 'flex justify-center'>
            <div class = "h-80 w-80 bg-contain rounded-lg bg-no-repeat" :style="getUrlImage(image)"></div>
        </div>
        <br>
        <div class = "text-2xl">
            My profile
        </div>
    <div class = "text-xl">
        {{name}}
    </div>
    <div class = "font-mono">
        {{education}}
    </div>
    <font-awesome-icon icon="fa-solid fa-bomb" />
    <br>
    </p>
</template>

<script>

export default {
    props: {
        name: {
            type: String,
            default: "A B"
        },
        education: {
            type: String,
            default: "KU 82 | Faculty of Science"
        },
        image: {
            type: String,
            default: "/assets/image/pfp.jpg",
        },
    },
    methods: {
        getUrlImage(imagePath) {
            return {'background-image':'url("./src/'+ imagePath +'")'};
        }
    },
};
</script>