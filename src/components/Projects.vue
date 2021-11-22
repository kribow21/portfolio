<template>
    <div>
        <h1>Project Highlights</h1>
        <v-container fluid>
            <v-row>
                <v-col cols="6" align="center" >
                <h2><a href="https://www.kbtweeter.ml/#/" target="_blank">Mock Twitter</a></h2>
                <h2><a href="https://github.com/kribow21/TweeterBackend.git" target="_blank">Backend Code</a></h2>
                <h2><a href="https://github.com/kribow21/TweeterFrontend.git" target="_blank">Frontend Code</a></h2>
                    <img src="../assets/tweeter.png">
                    <v-col>
                        <v-btn
                        href="https://www.javascript.com/"
                        target="_blank" small
                        rounded
                        >Javascript</v-btn>
                        <v-btn
                        href="https://vuejs.org/"
                        target="_blank" small
                        rounded
                        >VueJS</v-btn>
                        <v-btn
                        href="https://mariadb.org/"
                        target="_blank" small
                        rounded
                        >SQL / MariaDB</v-btn>
                    </v-col>
                    <v-col>
                        <v-btn
                        href="https://flask.palletsprojects.com/en/2.0.x/"
                        target="_blank" small
                        rounded
                        >Python / Flask</v-btn>
                        <v-btn
                        href="https://www.npmjs.com/package/cookies"
                        target="_blank" small
                        rounded
                        >Cookies</v-btn>
                        <v-btn
                        href="https://www.npmjs.com/package/axios"
                        target="_blank" small
                        rounded
                        >Axios</v-btn>
                    </v-col>
                </v-col>
                <v-col cols="6" align="center" >
                <h2><a href="https://www.seastheday.cc/#/" target="_blank">Seas The Day </a></h2>
                <h2><a href="https://github.com/kribow21/mvpFrontend.git" target="_blank">Frontend Code</a></h2>
                <h2><a href="https://github.com/kribow21/mvpBackend.git" target="_blank">Backend Code</a></h2>
                    <img src="../assets/seastheday.png">
                    <v-col>
                        <v-btn
                        href="https://www.javascript.com/"
                        target="_blank" small
                        rounded
                        >Javascript</v-btn>
                        <v-btn
                        href="https://vuejs.org/"
                        target="_blank" small
                        rounded
                        >VueJS</v-btn>
                        <v-btn
                        href="https://mariadb.org/"
                        target="_blank" small
                        rounded
                        >SQL / MariaDB</v-btn>
                    </v-col>
                    <v-col>
                        <v-btn
                        href="https://flask.palletsprojects.com/en/2.0.x/"
                        target="_blank" small
                        rounded
                        >Python / Flask</v-btn>
                        <v-btn
                        href="https://www.npmjs.com/package/cookies"
                        target="_blank" small
                        rounded
                        >Cookies</v-btn>
                        <v-btn
                        href="https://www.npmjs.com/package/axios"
                        target="_blank" small
                        rounded
                        >Axios</v-btn>
                    </v-col>
                </v-col>
            </v-row>
        </v-container>
    </div>
</template>

<script>
    export default {
        name : "Projects"
    }
</script>

<style scoped>
div{
    background-color: rgb(156, 138, 155);
    width: 100vw;
}
/*Mobile media rules*/
h1{
    padding-top: 2vh;
    font-family: 'Kreon', serif;
    padding-left: 15px;
    padding-right: 5vw;
}
h2{
    font-family: 'Kreon', serif;

}
img{
    width: 30vw;
    border-radius: 20px;
}
p{
    font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
h2 a{
    color: Black;
}
h2 a:hover{
    color: rgb(243, 217, 248);
}
</style>