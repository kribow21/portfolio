<template>
    <div>
        <h1>A Little About Me</h1>
        <p> I recently graduated from Innotech College where i completed the Full Stack Development Diploma. 
            Throughout the program I was able to put together some projects showcasing the technologies I learned. 
            If you're looking for an eager to learn developer, then you've come to the right place!
        </p>
        <h1>Technologies I've been working with recently:</h1>
        <div id="container">
            <ul>
                <li>GitHub</li>
                <li>HTML</li>
                <li>CSS / SCSS</li>
                <li>JavaScript</li>
                <li>VueJS</li>
            </ul>
            <ul>
                <li>Python</li>
                <li>Flask</li>
                <li>SQL</li>
                <li>MariaDB</li>
                <li>Apache</li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name : "AboutMe"
    }
</script>

<style scoped>
h1{
    padding-top: 4vh;
    font-family: 'Kreon', serif;
    padding-left: 15px;
}
div{
    background-color: rgb(156, 138, 155);
    width: 100vw;
}
p{
    padding-left: 15px;
    padding-top: 2vh;
    font-family: 'Segoe UI', Roboto, Oxygen, Ubuntu, Cantarell, 'Open Sans', 'Helvetica Neue', sans-serif;
}
#container{
    padding-left: 15px;
    display: grid;
    grid-template-columns: 0.2fr 0.2fr;
}
</style>