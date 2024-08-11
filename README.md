
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MI ana hermosa</title>
</head>
<style>
    body{
        margin:0;
        padding: 0;
        min-height: 100vh; 
        display: flex;
        align-items: center;
        justify-content: center;
        background:#0b1522 ;
    }
    .heart{
        height: 150px;
        width: 150px;
        background-color: #ff1b82;
        position: relative;
        transform: rotate(45deg);
        box-shadow: -20px 20px 150px #ff1b82;
        animation: palpitar 0.5s linear infinite alternate;
    }
    .contenido{
        position: fixed;
        margin-bottom: 50px;
        text-align: center;

    }
    h1{color: black};
    h2{color: white}
    @keyframes palpitar {
        0% {transform: rotate(45deg) scale(1.10);}
        80% {transform: rotate(45deg) scale(1.0);}
        100% {transform: rotate(45deg) scale(0.8);}
    }
    .heart::before{
        content: "";
        position: absolute;
        height: 150px;
        width: 150px;
        background: #ff1b82;
        right: 50%;
        border-radius: 50%;
        box-shadow: 20px 20px 150px #ff1b82;
    }
    .heart::after{
        content: "";
        position: absolute;
        height: 150px;
        width: 150px;
        background: #ff1b82;
        top: -50%;
        border-radius: 50%;
        box-shadow: 20px 20px 150px #ff1b82;
    }

</style>

<body>
    <div class="heart"></div>
    <div class="contenido"><h1>Te amo</h1><h2>Mi Ana<3</h2></div>
</body>
</html>
