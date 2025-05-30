<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="style/style.css">
</head>
<body>
    <header class="AuthRegistr">
        <h1>"Я буду кушац"</h1> 
    </header>
    <main class="forms">
        <form action="registr.php"  method="POST">
            <input type="text" name="login" placeholder="Введите логин" required>
            <input type="password" name="password" placeholder="Введите пароль" required minlength="6"> 
            <input type="text" name="fio" placeholder="Введите ФИО" required>
            <input type="phone" name="phone" placeholder="Введите Телефон" required>
            <input type="email" name="email" placeholder="Введите EMAIL" required>
            <input type="submit" value="Зарегистрироваться"/> <br>
            <a href="index.html">Есть аккаунт? Войти</a>
        </form>
        
    </main>
    <footer>
        "Я буду кушац" 2025. Сделал сайт Баянов Артём
    </footer>
</body>
</html>
