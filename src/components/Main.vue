<template>
    <main>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Kreon&display=swap" rel="stylesheet">
        <v-container fluid>
            <v-row justify="center">
                <v-img id="background"
                src="https://images.unsplash.com/photo-1519751138087-5bf79df62d5b?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxjb2xsZWN0aW9uLXBhZ2V8MXw5MDcwMDQ1OXx8ZW58MHx8fHw%3D&w=1000&q=80">
                </v-img>
                <h1>Hi! Im Kristin Bowles</h1>
                <h3>Motivated Full Stack Web Developer</h3>
                <v-avatar
                id="avitar"
                size="150"
                >
                <img src="../assets/Kheadshot.png" alt="Image of Kristin">
                </v-avatar>
                <v-btn
                id="connectBtn"
                elevation="2"
                rounded
                >Lets Connect</v-btn>
            </v-row>
            <v-row>
                <AboutMe/>
            </v-row>
            <v-row>
                <Projects/>
            </v-row>
        </v-container>
    </main>
</template>

<script>
import AboutMe from './AboutMe.vue'
import Projects from './Projects.vue'
    export default {
  components: { AboutMe, Projects  },
    name : "Main"
    }
</script>

<style scoped>
/*Mobile media rules*/
#connectBtn{
    position: absolute;
    margin-top: 25vh;
    color: rgb(156, 123, 199);
}
h1{
    position: absolute;
    font-size: 2rem;
    margin-top: 2vh;
    font-family: 'Kreon', serif;
}
h3{
    position: absolute;
    margin-top: 7vh;
    font-family: 'Kreon', serif;
}
#avitar{
    position: absolute;
    margin-top: 10vh;
    height: 6vh;
}
/*Tablet media rules*/
@media only screen and (min-width: 600px) {
#connectBtn{
    margin-top: 40vh;
}
h1{
    font-size: 2rem;
    margin-top: 12vh;
}
h3{
    margin-top: 18vh;
}
#avitar{
    margin-top: 22vh;
}
}
/*Desktop media rules*/
@media only screen and (min-width: 1025px) {
    #background{
        height:60vh;
    }
    #connectBtn{
    margin-top: 45vh;
    }
    h1{
    font-size: 3rem;
    }
    h3{
        margin-top: 20vh;
    }
    #avitar{
    margin-top: 24vh;
    }
}
</style>