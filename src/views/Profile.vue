<template>
    <profileCard name="Chantip Piriyabanjurd" image="/assets/image/mim.jpg"></profileCard>
    <profileCard name="Phumrapee Seonvanichakul" image="/assets/image/phum.jpg"></profileCard>
    <profileCard name="Jindamanee Sriharun"></profileCard>
</template>

<script>
import profileCard from "../components/Profile.vue";
export default {
    data()
    {
        return{
            name: "Jindamanee Sriharun",
            education: "KU 82 | Faculty of Science",

        }
    },
    components: {
        profileCard,
    },
};
</script>