<template>
    <h1> Here comes the content of the Homepage </h1>
    <div class="centre">
        <button type ="button1">BaseButton with custom margin </button>
        <button disabled>BaseButton disabled </button>
    </div>
</template>

<style scoped>

h1 {
    text-align:center;
    margin-top:200px
}

button {
    display: inline-block;
    background-color: #222;
    color : lightgreen;
    border-radius: 10px;
    text-align: center;
    font-size: 28px;
    padding: 20px;
    width: 500px;
    -webkit-transition: all 0.5s;
    -moz-transition: all 0.5s;
    -o-transition: all 0.5s;
    transition: all 0.5s;
    cursor: pointer;
    margin: 5px;
}

button:hover {
    background-color: rgb(221, 231, 231);
}

button:disabled,
button[disabled]{
  border: 1px solid #999999;
  background-color: #cccccc;
  color: #666666;
}

.centre{
  text-align: center;
}
</style>