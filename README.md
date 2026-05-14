<!DOCTYPE html>
<html lang="bn">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Button Website</title>

  <style>
    body{
      margin:0;
      padding:0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg,#4facfe,#00f2fe);
      display:flex;
      justify-content:center;
      align-items:center;
      height:100vh;
    }

    .container{
      width:90%;
      max-width:350px;
      background:white;
      padding:25px;
      border-radius:20px;
      text-align:center;
      box-shadow:0 0 20px rgba(0,0,0,0.2);
    }

    h1{
      margin-bottom:20px;
      color:#333;
    }

    .btn{
      display:block;
      width:100%;
      padding:15px;
      margin:12px 0;
      border:none;
      border-radius:12px;
      background:#007bff;
      color:white;
      font-size:18px;
      cursor:pointer;
      transition:0.3s;
    }

    .btn:hover{
      background:#0056b3;
      transform:scale(1.03);
    }
  </style>
</head>

<body>

  <div class="container">
    <h1>আমার ওয়েবসাইট</h1>

    <button class="btn" onclick="openLink('https://google.com')">
      Button 1
    </button>

    <button class="btn" onclick="openLink('https://youtube.com')">
      Button 2
    </button>

    <button class="btn" onclick="openLink('https://facebook.com')">
      Button 3
    </button>

    <button class="btn" onclick="openLink('https://telegram.org')">
      Button 4
    </button>

    <button class="btn" onclick="openLink('https://openai.com')">
      Button 5
    </button>
  </div>

  <script>
    function openLink(url){
      window.location.href = url;
    }
  </script>

</body>
</html>
