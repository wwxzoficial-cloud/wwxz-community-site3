<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>WWXZ Community</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: #000;
      color: #fff;
      text-align: center;
      border: 6px solid; border-image: linear-gradient(45deg, #6a00ff, #9f00ff, #00c3ff) 1;
      border-radius: 18px;
      
      animation: pageGlow 5s linear infinite;
    }
    .header {
      padding: 40px 0;
      background: url('https://i.imgur.com/wK4iY7M.jpeg') center/cover no-repeat;
      backdrop-filter: blur(5px);
    }
    .profile-img {
      width: 170px;
      height: 170px;
      border-radius: 50%;
      object-fit: cover;
      border: 4px solid transparent;
      background: linear-gradient(45deg, #6a00ff, #00c3ff, #6a00ff) border-box;
      animation: neonRotate 4s linear infinite;
      box-shadow: 0 0 20px #6a00ff, 0 0 30px #00c3ff;
      transition: transform .3s ease;
    }
    .profile-img:hover {
      transform: scale(1.07);
    }
    @keyframes neonRotate {
      0% { filter: hue-rotate(0deg); }
      100% { filter: hue-rotate(360deg); }
    }

    h1 {
      font-size: 48px;
      margin: 20px 0;
      color: #b682ff;
      text-shadow: 0 0 15px #a200ff;
    }

    .links img {
      width: 55px;
      margin: 10px;
      cursor: pointer;
      transition: transform .3s ease;
    }
    .links img:hover {
      transform: scale(1.15);
    }

    .nav button {
      padding: 12px 28px;
      margin: 6px;
      border: none;
      border-radius: 12px;
      background: linear-gradient(45deg, #6a00ff, #00c3ff);
      color: #fff;
      cursor: pointer;
      font-size: 17px;
      box-shadow: 0 0 12px #6a00ff;
      transition: transform .3s ease, box-shadow .3s ease;
    }
    .nav button:hover {
      transform: scale(1.1);
      box-shadow: 0 0 20px #00c3ff;
    }

    .section-title {
      font-size: 38px;
      margin-top: 40px;
      color: #9f81ff;
      text-shadow: 0 0 10px #5200ff;
    }

    .cards {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      margin-top: 20px;
      padding-bottom: 50px;
    }

    .card {
      background: rgba(255, 255, 255, 0.06);
      border-radius: 20px;
      margin: 15px;
      padding: 15px;
      width: 260px;
      border: 3px solid transparent;
      background: linear-gradient(#111, #111) padding-box,
      linear-gradient(45deg, #6a00ff, #00c3ff) border-box;
      box-shadow: 0 0 18px #6a00ff44;
      transition: transform .3s ease, box-shadow .3s ease;
    }
    .card:hover {
      transform: scale(1.05);
      box-shadow: 0 0 25px #00c3ff88;
    }

    .card img {
      width: 100%;
      border-radius: 12px;
    }

    .card-name {
      margin-top: 12px;
      font-size: 20px;
      color: #b682ff;
      text-shadow: 0 0 8px #6a00ff;
    }
  @keyframes borderRotate {
      0% { filter: hue-rotate(0deg); }
      100% { filter: hue-rotate(360deg); }
    }

    @keyframes pageGlow {
      0% { box-shadow: 0 0 25px #6a00ff; }
      50% { box-shadow: 0 0 35px #00c3ff; }
      100% { box-shadow: 0 0 25px #6a00ff; }
    }

    

</style>
</head>
<body>
  <div class="header">
    <img src="https://i.imgur.com/wK4iY7M.jpeg" class="profile-img" />
    <h1>WWXZ Community</h1>
    <div class="links">
      <a href="https://discord.gg/Q6f3uMnR" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/1384/1384060.png" /></a>
      <a href="https://www.youtube.com/@wwxzoficial" target="_blank"><img src="https://cdn-icons-png.flaticon.com/512/3670/3670157.png" /></a>
    </div>
    <div class="nav">
      <button>Executores</button>
      
    </div>
  </div>

  <h2 class="section-title">EXECUTORES</h2>
  <div class="cards">
    <a href="https://deltaexploits.gg/" target="_blank" class="card"><img src="https://i.imgur.com/ayUxVOR.png" /><p class='card-name'>Delta</p></a>
    <a href="https://wearedevs.net/d/Ronix" target="_blank" class="card"><img src="https://i.imgur.com/nNdzDTU.png" /><p class='card-name'>Ronix</p></a>
    <a href="https://wearedevs.net/d/Krnl" target="_blank" class="card"><img src="https://i.imgur.com/7jiVAQJ.png" /><p class='card-name'>KRNL</p></a>
    <a href="https://wearedevs.net/d/Solara" target="_blank" class="card"><img src="https://i.imgur.com/NxiHjMb.png" /><p class='card-name'>Solara</p></a>
    <a href="https://wearedevs.net/d/Fluxus%20Z" target="_blank" class="card"><img src="https://i.imgur.com/oQzRUxk.png" /><p class='card-name'>Fluxus</p></a>
    
  </div>
  <h2 class="section-title">SCRIPTS</h2>
  <div class="cards">
    <div class="card"><img src="https://i.imgur.com/uvhpowN.png" /><p class='card-name'>JL Hub</p></div>
  </div>
  <div style="margin-top:40px; padding-bottom:40px;">
      <button style="padding:14px 30px; border:none; border-radius:15px; background:linear-gradient(45deg,#6a00ff,#00c3ff); color:#fff; font-size:20px; cursor:pointer; animation:floatBtn 3s ease-in-out infinite; box-shadow:0 0 15px #6a00ff88;">
        Mais executores em breve
      </button>
    </div>

    <style>
      @keyframes floatBtn {
        0% { transform: translateY(0); }
        50% { transform: translateY(-8px); }
        100% { transform: translateY(0); }
      }
    </style>
</body>
</html>
