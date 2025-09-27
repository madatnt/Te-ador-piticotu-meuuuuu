# Te-ador-piticotu-meuuuuu
Multumesc ca faci parte din viata meaaa te iubiiii cel mai multtt
<!DOCTYPE html>
<html lang="ro">
<head>
    <meta charset="UTF-8">
    <title>Te iubesc</title>
    <style>
        body {
            background-color: #fff0f5;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
        }

        h1 {
            color: #d63384;
            font-size: 2.5em;
            margin-bottom: 40px;
        }

        .hearts {
            display: flex;
            gap: 30px;
        }

        .heart {
            width: 60px;
            height: 60px;
            background-color: red;
            position: relative;
            transform: rotate(-45deg);
        }

        .heart::before,
        .heart::after {
            content: "";
            width: 60px;
            height: 60px;
            background-color: red;
            border-radius: 50%;
            position: absolute;
        }

        .heart::before {
            top: -30px;
            left: 0;
        }

        .heart::after {
            left: 30px;
            top: 0;
        }
    </style>
</head>
<body>

    <h1>Te iubesc și te ador, piticotu’ meu 💖</h1>

    <div class="hearts">
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
        <div class="heart"></div>
    </div>

</body>
</html>
