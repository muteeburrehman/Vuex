<template>
    <h3>{{ counter }}</h3>
</template>

<script>
export default{
    computed: {
        counter(){
            return this.$store.state.counter * 2;
        }
    },
}
</script>