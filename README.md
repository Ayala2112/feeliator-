<!DOCTYPE html>
<html lang="he">
<head>
  <meta charset="UTF-8">
  <title>מחשבון רגשות</title>
  <style>
    body { font-family: Arial, sans-serif; text-align: center; margin-top: 50px; }
    button { margin: 10px; padding: 10px 20px; font-size: 16px; }
    #response { margin-top: 30px; font-size: 20px; }
  </style>
</head>
<body>
  <h1>מחשבון רגשות</h1>
  <button onclick="showResponse('שמחה')">שמחה</button>
  <button onclick="showResponse('עצב')">עצב</button>
  <button onclick="showResponse('עייפות')">עייפות</button>
  <div id="response"></div>

  <script>
    function showResponse(emotion) {
      const responses = {
        'שמחה': 'איזה כיף! המשיכי לחייך ולהפיץ אור 🌞',
        'עצב': 'הכל בסדר, גם ימים קשים עוברים. אני כאן בשבילך 💙',
        'עייפות': 'קחי נשימה עמוקה, אולי זה זמן למנוחה קלה 😴'
      };
      document.getElementById('response').innerText = responses[emotion];
    }
  </script>
</body>
</html>
מחשבון רגשות אינטראקטיבי שמחזיר משפט השראה, בדיחה או המלצה לפי מצב הרוח שלך
