<template>
<div>
    <ul class="a">
        <li>Home</li>
        <li style="float:right">Login</li>
    </ul>
</div>
</template>

<style scoped>
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #222;
    font-family: "Times New Roman", Times, serif;
}


li{
    float: left;
    display: block;
    color: lightgreen;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}


li:hover{
    background-color: green;
    transition: 0.5s;
}

</style>