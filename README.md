# Sam.github.io
<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>WhatsApp Pairing Code</title>

<style>
body{
    font-family: Arial, sans-serif;
    background:#0b141a;
    color:white;
    display:flex;
    justify-content:center;
    align-items:center;
    height:100vh;
}

.container{
    background:#202c33;
    padding:30px;
    border-radius:15px;
    width:350px;
    text-align:center;
}

h2{
    color:#25D366;
}

input{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    margin:15px 0;
}

button{
    width:100%;
    padding:12px;
    border:none;
    border-radius:8px;
    background:#25D366;
    color:white;
    font-size:16px;
    cursor:pointer;
}

.code{
    margin-top:20px;
    padding:15px;
    background:#111b21;
    border-radius:10px;
    font-size:22px;
    letter-spacing:3px;
}
</style>
</head>

<body>

<div class="container">
    <h2>WhatsApp Pairing</h2>

    <input
        type="text"
        placeholder="237XXXXXXXXX"
        id="phone"
    >

    <button onclick="generateCode()">
        Générer le code
    </button>

    <div class="code" id="code">
        ---- ----
    </div>
</div>

<script>
function generateCode(){
    document.getElementById("code").innerHTML =
    "SAMY-1234";
}
</script>

</body>
</html>
