<template>
    <div>
        <h1>Project Highlights</h1>
        <v-container>
            <v-row>
                <v-col cols="6" order-sm>
                <h2>Mock Twitter</h2>
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
                <v-col cols="6" order-sm>
                <h2>Seas The Day</h2>
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
h1, h2{
    padding-top: 2vh;
    font-family: 'Kreon', serif;
    padding-left: 5vw;
    padding-right: 5vw;
}
img{
    width: 30vw;
    border-radius: 20px;
}
p{
    font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}

</style>