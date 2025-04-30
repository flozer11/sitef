<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Курс з JavaScript</title>

  <!-- Підключення бібліотек -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <script src="https://cdn.jsdelivr.net/npm/lodash@4.17.21/lodash.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/react/18.2.0/umd/react.production.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/react-dom/18.2.0/umd/react-dom.production.min.js"></script>

  <!-- Вбудовані стилі -->
  <style>
    body {
      background-color: #f9f9f9;
    }
    h1 {
      color: #0d6efd;
    }
    .container {
      margin-top: 40px;
    }
  </style>
</head>
<body>

<div class="container py-5">
  <h1 class="text-center mb-4">Онлайн-курс з JavaScript</h1>
  <p class="text-center">Вивчайте JavaScript з нуля до просунутого рівня. Перегляньте програму курсу нижче.</p>

  <div class="row mt-5">
    <div class="col-md-4">
      <h4>Базові знання</h4>
      <ul>
        <li>Змінні</li>
        <li>Типи даних</li>
        <li>Функції</li>
      </ul>
    </div>
    <div class="col-md-4">
      <h4>Практика</h4>
      <ul>
        <li>Міні-проєкти</li>
        <li>Побудова To-Do List</li>
        <li>Гра “Вгадай число”</li>
      </ul>
    </div>
    <div class="col-md-4">
      <h4>Переваги</h4>
      <ul>
        <li>Доступ назавжди</li>
        <li>Сертифікат</li>
        <li>Підтримка ментора</li>
      </ul>
    </div>
  </div>

  <div class="text-center mt-5">
    <button id="register" class="btn btn-success">Зареєструватись</button>
  </div>

  <div id="reaction" class="text-center mt-3 text-success fw-bold"></div>
</div>

<!-- Вбудований скрипт -->
<script>
  $(document).ready(function () {
    $('#register').click(function () {
      $('#reaction').text('Дякуємо! Ми зв’яжемось із вами найближчим часом.');
    });
  });
</script>

</body>
</html>
