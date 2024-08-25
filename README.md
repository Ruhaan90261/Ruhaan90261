<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Request for Information</title>
    <style>
        /* Add your CSS styles here */
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px; /* This is where you add the code */
        }
        button {
            font-size: 18px;
            padding: 10px 20px;
            margin: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>

    <h1>Khushi didi, kyaa tum aapni friend Richa ki information aur photos ki jo baat kar rahi thi woh de sakti ho kyaa?</h1>
    <p>Pls dedona, pyaari behen ho na... 😇</p>

    <button id="yesButton">Haa, Jarur!</button>
    <button id="noButton">Naa, Bilkul Nahi!</button>

    <script>
        document.getElementById("noButton").onclick = function() {
            alert("Aare plss dedona pyaari behen ho na, ek chocolate khila dunga aapko mai 🍫");
        };

        document.getElementById("yesButton").onclick = function() {
            alert("Shukriya! Aap bohot acchi behen ho 😊");
        };
    </script>

</body>
</html>
