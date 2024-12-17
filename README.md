html

<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Анкета</title>
</head>
<body>

    <h1>Анкета</h1>

    <form>

        <h2>Личные данные</h2>

        <label for="surname">Фамилия:</label>
        <input type="text" id="surname" name="surname" required><br><br>

        <label for="name">Имя:</label>
        <input type="text" id="name" name="name" required><br><br>

        <label for="patronymic">Отчество:</label>
        <input type="text" id="patronymic" name="patronymic"><br><br>

        <label for="birthdate">Дата рождения:</label>
        <input type="date" id="birthdate" name="birthdate" required><br><br>

        <label>Пол:</label><br>
        <input type="radio" id="male" name="gender" value="male">
        <label for="male">Мужской</label><br>
        <input type="radio" id="female" name="gender" value="female">
        <label for="female">Женский</label><br><br>

        <h2>Контактная информация</h2>

        <label for="email">Электронная почта:</label>
        <input type="email" id="email" name="email" required><br><br>

        <label for="phone">Телефон:</label>
        <input type="tel" id="phone" name="phone"><br><br>

        <input type="submit" value="Отправить">

    </form>

</body>
</html>
