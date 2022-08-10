<template>
<h2>{{ name }} Pinguin Girl</h2>
<img src="vue-mission-02/src/assets/images/pinguin.jpeg" alt="jeune pinguine"/>
</template>

<script>
export default {
    name: 'PinguinGirl',
    props: {
        name: String
    }
}
</script>

<style>
</style>