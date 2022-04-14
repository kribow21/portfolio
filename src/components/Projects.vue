<template>
    <main>
    <h1>Project Highlights</h1>
        <div class="container">
            <div class="project">
                <h2><a href="https://www.kbtweeter.click/#/" target="_blank">Mock Twitter</a></h2>
                <p>Please contact me if you would like <br>to sign in using an existing user</p>
                <h2><a href="https://github.com/kribow21/TweeterFrontend.git" target="_blank">Frontend Code</a></h2>
                <h2><a href="https://github.com/kribow21/TweeterBackend.git" target="_blank">Backend Code</a></h2>
                <img src="../assets/tweeter.png" alt="Mock Tweeter Login Page">
                <section class="tools">
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
                    <br>                       
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
                </section>
            </div>
            <div class="project">
                <h2><a href="https://www.seastheday.cc/#/" target="_blank">Seas The Day </a></h2>
                <p>An online journal where you can create entries based on a <br>provided prompt and input your mood to display on the calendar</p>
                <h2><a href="https://github.com/kribow21/mvpFrontend.git" target="_blank">Frontend Code</a></h2>
                <h2><a href="https://github.com/kribow21/mvpBackend.git" target="_blank">Backend Code</a></h2>
                <img src="../assets/seastheday.png" alt="SeastheDay Online Journal">
                <section class="tools">
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
                    <br>                       
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
                </section>
            </div>
            <div class="project">
                <h2><a href="https://centrespa.click/#/" target="_blank">Centre Spa Mock Homepage</a></h2>
                <p>Using vuetify and flexbox to follow the design <br>of this spa's homepage, see git readme file for original website</p>
                <h2><a href="https://github.com/kribow21/spa.git" target="_blank">Frontend Code</a></h2>
                <img src="../assets/spa.png" alt="Mock Spa Page Centre Spa">
            </div>
            <div class="project">
                <h2>Comming Soon!</h2>
                <p>A website for a nonprofit called C.O.P.E <br>(Community Outreach Program Enhancement)</p>
            </div>
        </div>
    </main>
</template>

<script>
    export default {
        name : "Projects"
    }
</script>

<style lang="scss" scoped>
/*Mobile media rules*/
main{
    background-color: rgb(156, 138, 155);
    width: 100%;
}
h2,h2 a{
    color: Black;
    font-family: 'Kreon', serif;
}
h1{
    font-family: 'Kreon', serif;
    padding-left: 15px;
}
.container{
    display: flex;
    flex-direction: column;
    row-gap: 15px;
    justify-content: space-evenly;

}
img{
    width: 80vw;
    border-radius: 20px;
}
/*Tablet media rules*/
@media only screen and (min-width: 600px) {
    .container{
        flex-direction: row;
        column-gap: 6vw;
        row-gap: 6vh;
        align-items: baseline;
        justify-content: start;
        flex-wrap: wrap;
    }
    img{
        width: 30vw;
    }
}
/*Desktop media rules*/
@media only screen and (min-width: 1025px) {
    h2 a:hover{
        color: rgb(243, 217, 248);
    }
}
</style>