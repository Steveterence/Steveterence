## je suis NLAM KIGOUE STEVE TERENCE, passionné de cyber sécurité, programmation web, et du infographie 
### analyste soft junior cyber sécurité | élève ingénieur en art numérique 

<img src="https://github-profile-trophy.vercel.app/?username=Steveterence&row=1&theme=darkhub&margin-w=15&no-bg=true" alt="GitHub Trophy">

### Github Stats 🔥
<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com?user=Steveterence&theme=radical&date_format=j%20M%5B%20Y%5D&sideLabels=DDB225" alt="benjaminfehem" /></p>
<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=Steveterence&show_icons=true&locale=en&layout=compact&theme=cobalt" alt="Steveterence" /></p>
<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=Steveterence&show_icons=true&locale=en&theme=tokyonight" alt="Steveterence" /></p>
Voici un exemple simple de code HTML + CSS qui représente un logo en forme de "V" avec le nom TG intégré :


---

✅ Résultat attendu :

Un "V" stylisé en SVG (ou CSS).

Le texte "TG" à côté ou intégré dans le "V".



---

🔧 Code HTML + CSS :

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Logo TG en V</title>
  <style>
    body {
      background-color: #f4f4f4;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .logo {
      display: flex;
      align-items: center;
      font-family: 'Arial', sans-serif;
    }

    .v-shape {
      width: 50px;
      height: 50px;
      position: relative;
      margin-right: 10px;
    }

    .v-shape::before,
    .v-shape::after {
      content: '';
      position: absolute;
      bottom: 0;
      width: 10px;
      height: 100%;
      background: #007bff;
    }

    .v-shape::before {
      left: 0;
      transform: rotate(25deg);
      transform-origin: bottom left;
    }

    .v-shape::after {
      right: 0;
      transform: rotate(-25deg);
      transform-origin: bottom right;
    }

    .logo-text {
      font-size: 32px;
      font-weight: bold;
      color: #333;
    }
  </style>
</head>
<body>
  <div class="logo">
    <div class="v-shape"></div>
    <div class="logo-text">TG</div>
  </div>
</body>
</html>


---
