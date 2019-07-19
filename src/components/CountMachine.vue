<template>
    <div>
        <button v-on:click="decrease">-</button>
        <span>{{count}}</span>
        <button v-on:click="increase">+</button>
    </div>
</template>

<script>
    export default {
        name: "CountMachine",
        data() {
            return {count: 0}  // count 初始值为0
        },
        methods: {
            decrease() {
                this.count--;
            },

            increase() {
                this.count++;
            }
        }
    }
</script>

<style scoped>
</style>