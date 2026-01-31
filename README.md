# dolylolyy
<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <title>Walentynka? ❤️</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #ffe6eb;
      text-align: center;
      padding-top: 100px;
    }
    h1 {
      font-size: 36px;
    }
    button {
      font-size: 20px;
      padding: 15px 30px;
      margin: 15px;
      border: none;
      border-radius: 12px;
      cursor: pointer;
    }
    #yes {
      background: #ff4d6d;
      color: white;
    }
    #no {
      background: #cccccc;
    }
  </style>
</head>
<body>

<h1>Czy zostaniesz moją walentynką? 💖</h1>

<button id="yes" onclick="yesClick()">TAK 💘</button>
<button id="no" onclick="noClick()">NIE 😢</button>

<p id="message"></p>

<script>
function yesClick() {
  document.body.innerHTML = "<h1>YAY!!! 🥹💖<br>Wiedziałam!!!</h1><p>Happy Valentine's Day 💘</p>";
}

function noClick() {
  document.getElementById("message").innerText =
    "Ej nooo 😭 spróbuj jeszcze raz...";
}
</script>

</body>
</html>
