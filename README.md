```html
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Can You Be My Date?? 💕</title>

<style>

body{
    font-family: 'Arial', sans-serif;
    background: #ffe6f0;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
    text-align:center;
}

.container{
    background:white;
    padding:40px;
    border-radius:15px;
    box-shadow:0 10px 25px rgba(0,0,0,0.2);
}

h1{
    color:#ff4d6d;
    font-size:38px;
}

.gif{
    width:200px;
    margin:20px 0;
}

button{
    padding:12px 30px;
    font-size:18px;
    border:none;
    border-radius:10px;
    margin:10px;
    cursor:pointer;
}

#yes{
    background:#ff4d6d;
    color:white;
}

#no{
    background:#ccc;
}

</style>
</head>

<body>

<div class="container">

<h1>CAN YOU BE MY DATE? 💕</h1>

<img class="gif"
src="https://media.tenor.com/EBV7OT7ACfwAAAAj/u-u-qua-qua-u-quaa.gif">

<br>

<button id="yes" onclick="yesClick()">Yes 💘</button>
<button id="no" onclick="moveNo()">No 😢</button>

</div>

<script>

function yesClick(){
    window.location.href="https://sahilgogna.github.io/v-day/yes.html";
}

function moveNo(){
    const btn = document.getElementById("no");
    btn.style.position="absolute";
    btn.style.top=Math.random()*80+"%";
    btn.style.left=Math.random()*80+"%";
}

</script>

</body>
</html>
```
