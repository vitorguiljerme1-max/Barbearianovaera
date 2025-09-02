git init
git add index.html
git commit -m "Primeiro commit - site Barbearia Nova Era"
git branch -M main
git remote add origin https://github.com/vitorguiljerme1-max/barbearia-nova-era.git
git push -u origin main

<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Barbearia Nova Era</title>
  <style>
    body { font-family: Arial; text-align: center; margin:50px; background:#f5f5f5;}
    h1{color:#222; font-size:2.5em;}
    .social{margin-bottom:30px; font-size:1.2em;}
    .social a{margin:0 10px; color:#1a1a1a; text-decoration:none;}
    iframe{width:80%; height:600px; border:1px solid #ccc; margin-top:20px; border-radius:8px;}
  </style>
</head>
<body>
  <h1>Barbearia Nova Era</h1>
  <div class="social">
    Siga-nos no Instagram:
    <a href="https://www.instagram.com/pedrinhobarber_001" target="_blank">@pedrinhobarber_001</a>
    <a href="https://www.instagram.com/marcos_paul0_o" target="_blank">@marcos_paul0_o</a>
  </div>
  <iframe src="https://74a37aca6803.ngrok-free.app/form/295f7bbd-1beb-45be-8dd2-de30b094f0bf" frameborder="0"></iframe>
</body>
</html>
