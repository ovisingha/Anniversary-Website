<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>For My Baby 💖</title>
  <style>
    body {
      background: linear-gradient(to right, #f8cdda, #fbd786);
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      flex-direction: column;
    }

    h1 {
      font-size: 2rem;
      margin-bottom: 30px;
      color: #4b2c4f;
    }

    .buttons {
      display: flex;
      gap: 20px;
    }

    button {
      padding: 12px 25px;
      font-size: 18px;
      border: none;
      border-radius: 30px;
      cursor: pointer;
      transition: all 0.3s ease;
    }

    .yes {
      background-color: #ff5e91;
      color: white;
    }

    .yes:hover {
      background-color: #ff2e70;
    }

    .no {
      background-color: #dcdcdc;
      color: #555;
      pointer-events: none;
    }

    .card {
      display: none;
      margin-top: 40px;
      background: white;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 0 20px rgba(0,0,0,0.1);
      max-width: 400px;
      text-align: center;
      animation: fadeIn 1s ease forwards;
    }

    .card.show {
      display: block;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <h1>Will you be mine forever, Baby? 💖</h1>

  <div class="buttons">
    <button class="yes" onclick="showCard()">Yes</button>
    <button class="no">No</button>
  </div>

  <div class="card" id="loveCard">
    <h2>Forever Yours 💌</h2>
    <p>
      From the day you said "Yes", my life changed forever.<br>
      You're not just my love — you're my peace, my smile, my everything.<br><br>
      <strong>Happy 2 Years Anniversary, Baby 🩷</strong><br>
      Let’s write many more beautiful chapters together...
    </p>
  </div>

  <script>
    function showCard() {
      document.getElementById("loveCard").classList.add("show");
    }
  </script>
</body>
</html>
