<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>تسبيح لله</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
    }
    #counter {
        font-size: 24px;
        margin-bottom: 20px;
    }
    button {
        font-size: 18px;
        padding: 10px 20px;
        margin: 10px;
        cursor: pointer;
    }
</style>
</head>
<body>
    <h1>تسبيح لله</h1>
    <div id="counter">0</div>
    <button onclick="count()">تسبيح</button>
    <button onclick="reset()">إعادة تعيين</button>

    <script>
        let countDisplay = document.getElementById('counter');
        let count = 0;

        function count() {
            count++;
            countDisplay.innerText = count;
        }

        function reset() {
            count = 0;
            countDisplay.innerText = count;
        }
    </script>
</body>
</html>
