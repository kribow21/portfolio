<template>
    <div>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Kreon&display=swap" rel="stylesheet">
        <v-container>
            <v-row justify="center">
                <v-img
                src="https://images.unsplash.com/photo-1519751138087-5bf79df62d5b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXw5MDcwMDQ1OXx8ZW58MHx8fHw%3D&w=1000&q=80">
                </v-img>
                <h1>Hi! Im Kristin Bowles</h1>
                <h3>Motivated Full Stack Web Developer</h3>
                <v-avatar
                id="avitar"
                size="200"
                >
                <img src="../assets/Kheadshot.png" alt="Image of Kristin">
                </v-avatar>
                <v-btn
                id="connectBtn"
                elevation="2"
                rounded
                >Lets Connect</v-btn>
            </v-row>
        </v-container>
    </div>
</template>

<script>
    export default {
        name : "Top"
    }
</script>

<style scoped>
div{
    width: 100vw;
    height: 60vh;
    margin: 0;
    padding: 0;
}
#connectBtn{
    position: absolute;
    margin-top: 52vh;
    color: rgb(156, 123, 199);
}
h1{
    position: absolute;
    font-size: 2rem;
    margin-top: 12vh;
    font-family: 'Kreon', serif;
}
h3{
    position: absolute;
    margin-top: 21vh;
    font-family: 'Kreon', serif;
}
#avitar{
    position: absolute;
    margin-top: 26vh;
}
@media only screen and (min-width: 600px) {
h1{
    font-size: 3rem;
}
}
</style>