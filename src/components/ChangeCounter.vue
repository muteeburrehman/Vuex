<template>
    <button @click="addOne">Add 2</button>
</template>

<script>
export default{
    methods: {
        addOne(){
            // this.$store.state.counter = this.$store.state.counter + 2;
            this.$store.commit('increment');
        }
    }
}
</script>