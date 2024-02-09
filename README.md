<!DOCTYPE html>
<html lang="es">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>♥ Quiere Salir Conmigo ♥</title>
  <style>
    body {
      background-color: crimson;
      text-align: center;
    }

  .body__title {
      color: white;
    }

  .body__img {
      width: 100%;
      max-width: 512px;
      border-radius: 50%;
    }
  </style>
</head>

<body>
  <div class="body">
    <h1 class="body__title">♥ Quiere Salir Conmigo ♥</h1>
    <img src="https://frikimaestro.com/wp-content/uploads/2019/10/0005-3.jpg" alt="Foto D My" class="body__img" />
    <br>
    <button id="yes">🌚 Si 🌚</button>
    <button id="no">😭 No 😭</button>
  </div>

  <script>
    const buttonSi = document.getElementById('yes');
    const buttonNo = document.getElementById('no');

    const serNovios = () => {
      alert('💞 Lo que te Espera 💞');
      alert('😱 Prepárate 😱');
    };

    const evitarQueRompaTuCorazon = () => {
      buttonNo.style.position = 'absolute';
      buttonNo.style.top = (Math.random() * window.innerHeight + 'px');
      buttonNo.style.left = (Math.random() * window.innerWidth + 'px');
    };

    buttonSi.addEventListener('click', serNovios);
    buttonNo.addEventListener('mouseover', evitarQueRompaTuCorazon);
  </script>
</body>

</html>
