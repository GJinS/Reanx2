<template>
  <div>
    <button class = "p-2 bg-neutral-300 hover:bg-stone-500 hover:text-zinc-50" @click="count++">Add 1</button>
    <div>Count is : {{count}}</div>
  </div>
</template>

<script>
export default {
    data() {
        return{
            count: 0
        }
    }
}
</script>

<style>

</style>