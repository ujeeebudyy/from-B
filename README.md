<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FROM B</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1 class="h1-navbar">untuk wanita bernama Dinda Akila Aulia gw cuma mau bilang....</h1>
        <button id="revealButton">Reveal</button>

        
        <div id="heartContainer" class="hidden">
              <div class="heart">
                <img src="d5269a14-abda-4013-8063-09102bab4c46.jpeg" width="30%" height="30%"/>
              </div>
        <p class="p-content">LU CAKEP BANGET SUMPAH</p>
        </div>
        
    
</div>
</body>
<script>
    document.getElementById('revealButton').addEventListener('click', function() {
        document.getElementById('heartContainer').classList.remove('hidden');
    });
</script>
</html>
