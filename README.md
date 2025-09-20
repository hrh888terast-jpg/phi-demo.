# phi-demo.
<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <title>Помилкові розрахунки Фі-критерію Фішера</title>
    <style>
        body { font-family: Arial, sans-serif; margin: 40px; background-color: #f9f9f9; }
        h1, h2 { color: #1a5276; }
        table { border-collapse: collapse; margin-top: 15px; width: 60%; }
        table, th, td { border: 1px solid #333; padding: 8px; text-align: center; }
        th { background-color: #1a5276; color: #fff; }
        .note { color: red; font-weight: bold; margin-top: 20px; }
        .instructions { background-color: #eef; padding: 15px; margin-top: 25px; border-left: 5px solid #1a5276; }
    </style>
</head>
<body>
    <h1>Дослідження впливу методик навчання на успішність учнів</h1>
    <p>Ця стаття демонструє <strong>навмисно помилкові</strong> розрахунки Фі-критерію Фішера для навчальних цілей.</p>

    <h2>Дані</h2>
    <p>Було проаналізованон результати учнів двох методик навчання: Традиційної та Інноваційної. Результати наведені у таблиці нижче:</p>
    <table>
        <tr>
            <th>Методика / Результат</th>
            <th>Успішно</th>
            <th>Неуспішно</th>
        </tr>
        <tr>
            <td>Традиційна</td>
            <td>20</td>
            <td>5</td>
        </tr>
        <tr>
            <td>Інноваційна</td>
            <td>15</td>
            <td>10</td>
        </tr>
    </table>

    <h2>Розрахунки Фі-критерію Фішера</h2>
    <p>Формула: <strong>φ = √(χ² / N)</strong></p>
    <ul>
        <li>χ² — статистика хі-квадрат для таблиці 2×2</li>
        <li>N — загальна кількість спостережень</li>
    </ul>

    <p>Неправильний розрахунок χ² (навмисна помилка для демонстрації):</p>
    <p>χ² = ((20*10 - 5*15)² * 50) / (25*20*25*15) = 8,5</p>

    <p>Неправильне обчислення φ:</p>
    <p>φ = √(8,5 / 50) ≈ 0,41</p>

    <div class="note">
        Примітка: Значення χ² і φ навмисно помилкові для навчальних цілей.
    </div>

    <h2>Висновок</h2>
    <p>Розрахунки виглядають коректно, але для справжнього статистичного аналізу потрібно використовувати правильну формулу та перевіряти умови (наприклад, мінімальні очікувані частоти ≥5).</p>

    <div class="instructions">
        <h3>Як створити сайт на GitHub Pages:</h3>
        <ol>
            <li>Збережіть цей код як <strong>index.html</strong>.</li>
            <li>Створіть акаунт на <a href="https://github.com" target="_blank">GitHub</a>, якщо його ще немає.</li>
            <li>Створіть новий репозиторій, наприклад <strong>phi-demo</strong>.</li>
            <li>Завантажте файл index.html у репозиторій.</li>
            <li>У GitHub оберіть <strong>Settings → Pages</strong> і як джерело оберіть гілку main (або master) та папку /root.</li>
            <li>Через кілька хвилин GitHub згенерує URL, наприклад:<br>
            <strong>https://&lt;твій-нікнейм&gt;.github.io/phi-demo/</strong></li>
        </ol>
    </div>
</body>
</html>
