<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy Birthday! 🎂</title>
    <style>
        body { display: flex; justify-content: center; align-items: center; height: 100vh; background: linear-gradient(135deg, #f5f7fa 0%, #c3cfe2 100%); font-family: sans-serif; margin: 0; }
        .card { background: white; padding: 30px; border-radius: 15px; box-shadow: 0 10px 20px rgba(0,0,0,0.1); text-align: center; max-width: 350px; cursor: pointer; }
        h1 { color: #ff6b6b; }
        .hidden-wish { display: none; color: #6c5ce7; font-weight: bold; margin-top: 15px; }
    </style>
</head>
<body>
    <div class="card" onclick="showWish()">
        <h1>🎂 Happy Birthday! ✨</h1>
        <p>မွေးနေ့မှာ ပျော်ရွှင်ပါစေ။</p>
        <p style="color: #aaa; font-size: 12px;">(ကဒ်လေးကို နှိပ်ကြည့်ပါဦး 🎁)</p>
        <div id="wish" class="hidden-wish">မွေးနေ့မှစပြီး လိုအင်ဆန္ဒတွေအကုန် ပြည့်ဝပါစေ။ 🎉❤️</div>
    </div>
    <script>
        function showWish() { document.getElementById('wish').style.display = 'block'; }
    </script>
</body>
</html>
