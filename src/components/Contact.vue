<template>
    <div>
        <h1>Contact Info</h1>
        <h3>Email : <a href="mailto:kristinbowles21@gmail.com"> kristinbowles21@gmail.com</a></h3>
        <h3>Phone : <a href="tel:7805010674">780-501-0674</a></h3>
        <h3>LinkedIn : <a href="https://www.linkedin.com/in/kristin-bowles-3b909121a/" target="_blank">Kristin Bowles</a></h3>
    </div>
</template>

<script>
    export default {
        name : "Contact"
    }
</script>

<style scoped>
div{
    background-color: rgb(156, 138, 155);
    width: 100%;
    padding-bottom: 5vh;
}
h1, h3{
    font-family: 'Kreon', serif;
    padding-top: 2vh;
    padding-left: 15px;
}
h3 a{
    color: Black;
}
h3 a:hover{
    color: rgb(243, 217, 248);
}
</style>