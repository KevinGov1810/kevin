<template>
    <h1> Here comes the content of the Homepage </h1>
    <div class="centre">
        <button class="button-primary">BaseButton with custom margin </button>
        <button disabled>BaseButton disabled </button>
        <button class="button-warn">BaseButton with color props</button>
        <button class="button-danger">BaseButton with color props</button>
    </div>
</template>

<script>
</script>


<style scoped>

h1 {
    text-align:center;
    margin-top:200px
}

button {
    display: inline-block;
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

button:disabled,
button[disabled]{
  border: 1px solid #999999;
  background-color: #cccccc;
  color: #666666;
}

/*Primary css*/
.button-primary{
    background-color : #42b983;
}
.button-primary:hover{
    background-color : #4cce93;
}
.button-primary:focus{
    color : #47d696;
}

/*Warn css*/
.button-warn{
    background-color : #ff5722;
}
.button-warn:hover{
    background-color : #ff7043;
}
.button-warn:focus{
    color : #ff8a65;
}

/*Danger css*/
.button-danger{
    background-color : #e53935;
}
.button-danger:hover{
    background-color : #ef5350;
}
.button-danger:focus{
    color : #e57373;
}

.centre{
  text-align: center;
}
</style>