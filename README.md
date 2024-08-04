<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مولد الأرقام العشوائية المتقدم</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin-top: 50px;
        }
        #result {
            font-size: 2em;
            margin-top: 20px;
        }
        button {
            padding: 10px 20px;
            font-size: 1em;
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/mersenne-twister/1.1.0/mt.min.js"></script>
</head>
<body>
    <h1>مولد الأرقام العشوائية المتقدم</h1>
    <button onclick="generateRandomN![1722798654919813610270792671068](https://github.com/user-attachments/assets/bf58377f-7b93-43b2-84c0-6d04a3972c20)
umber()">توليد رقم عشوائي</button>
    <div id="result">0</div>

    <script>
        let mt = new MersenneTwister();

        function generateRandomNumber() {
            // توليد رقم عشوائي باستخدام Mersenne Twister
            var min = 1;
            var max = 100;
            var randomNumber = Math.floor(mt.random() * (max - min + 1)) + min;

            // تحديث عنصر النتيجة لعرض الرقم العشوائي
            document.getElementById("result").innerText = randomNumber;
        }
    </script>
</body>
</html># mahmoud
