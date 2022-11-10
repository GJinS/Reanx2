<template>
    <div class = "text-amber-900 bg-red-100 hover:text-pink-400 hover:bg-orange-50">
        <RouterLink to="/">Home</RouterLink>
    </div>
    <div class = "text-amber-900 bg-red-100 hover:text-pink-400 hover:bg-orange-50">
        <RouterLink to="/profile">Profile</RouterLink>
    </div>
    <div class = "text-amber-900 bg-red-100 hover:text-pink-400 hover:bg-orange-50">
        <RouterLink to="/form">Form</RouterLink>
    </div>
    <slot></slot>
</template>

<script>
export default {

}
</script>

<style></style>