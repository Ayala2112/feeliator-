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
  <button onclick="showResponse('תסכול')">תסכול</button>
  <button onclick="showResponse('אכזבה')">אכזבה</button>
  <button onclick="showResponse('ייאוש')">ייאוש</button>
  <button onclick="showResponse('אהבה')">אהבה</button>
  <button onclick="showResponse('הצפה')">הצפה</button>
  <button onclick="showResponse('בכי')">בכי</button>
  <div id="response"></div>

  <script>
    function showResponse(emotion) {
      var responseText = '';

      if (emotion === 'שמחה') {
        responseText = "איזה כיף! המשיכי לחייך ולהפיץ אור 🌞";
      } else if (emotion === 'עצב') {
        responseText = "הכל בסדר, גם ימים קשים עוברים. אני כאן בשבילך 💙";
      } else if (emotion === 'עייפות') {
        responseText = "נראה שאת צריכה מנוחה. זה בסדר להרגיש ככה.";
      } else if (emotion === 'תסכול') {
        responseText = "את לא לבד, תסכול זה רגש טבעי.";
      } else if (emotion === 'אכזבה') {
        responseText = "לפעמים אנחנו מצפים לדברים יותר, זה אכזב.";
      } else if (emotion === 'ייאוש') {
        responseText = "זה יכול להיות קשה, אבל יש תמיד תקווה.";
      } else if (emotion === 'אהבה') {
        responseText = "אהבה תמיד מחממת את הלב!";
      } else if (emotion === 'הצפה') {
        responseText = "לפעמים הכל משתלט עלינו, זה בסדר להרגיש כך.";
      } else if (emotion === 'בכי') {
        responseText = "בכי זה טבעי, זה יכול לעזור לשחרר רגש.";
      }

      document.getElementById("response").innerText = responseText;
    }
  </script>
</body>
</html>
'קחי נשימה עמוקה, אולי זה זמן למנוחה קלה 😴'
      };
      document.getElementById('response').innerText = responses[emotion];
    }
  </script>
</body>
</html>
מחשבון רגשות אינטראקטיבי שמחזיר משפט השראה, בדיחה או המלצה לפי מצב הרוח שלך
