<template>
    <div>
        <h1>A Little About Me</h1>
        <p> I recently graduated from Innotech College where I completed the 6 month Full Stack Development Diploma. 
            Throughout the program I was able to put together some full stack projects showcasing the technologies I learned, from requirements gathered and prototyping
            to writing and deploying the code onto a virtual Google cloud.
            From my previous experience in childcare and development to creating delicious treats in kitchens, my goal as a new developer is to
            bring creativity and be a positive contributor to clients and my future team. I look forward to continuing my growth
            within a company that encourages learning and supports the development of their employees!
        </p>
        <h1>Technologies I've been working with recently:</h1>
        <div id="container">
            <ul>
                <li>GitHub</li>
                <li>HTML</li>
                <li>CSS / SCSS</li>
                <li>JavaScript</li>
                <li>VueJS / Vuex / VueRouter</li>
            </ul>
            <ul>
                <li>Python</li>
                <li>Flask</li>
                <li>SQL</li>
                <li>MariaDB</li>
                <li>Apache</li>
                <li>Figma</li>
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