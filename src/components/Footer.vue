<template>
    <div>
    <v-footer id="foot">
        <v-col
        class="text-center"
        cols="12"
        >
        <v-card-text>
            Thanks for Visiting
        </v-card-text>
        {{ new Date().getFullYear() }} — <strong>Kristin Bowles</strong>
        </v-col>
    </v-footer>
    </div>
</template>

<script>
    export default {
        name : "Footer"
    }
</script>

<style scoped>
#foot{
    background-color: rgb(189, 177, 188);

}
</style>