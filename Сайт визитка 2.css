<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Моя визитка</title>
<style>
  body {
    font-family: 'Arial', sans-serif;
    margin: 0;
    background-color: #e0f7fa;
    color: #333;
  }
  .container {
    max-width: 800px;
    margin: 50px auto;
    background-color: #ffffff;
    padding: 30px;
    border-radius: 15px;
    box-shadow: 0 4px 12px rgba(0,0,0,0.1);
    text-align: center;
  }
  h1 {
    font-size: 2.5em;
    margin-bottom: 10px;
    color: #040003;
  }
  .photo {
    width: 150px;
    height: auto;
    border: 4px solid #040103;
    border-radius: 50%;
    display: block;
    margin: 0 auto 15px auto;
  }

  /* Контакты по центру под фото */
  section.contacts {
    margin-bottom: 20px;
    text-align: center;
  }
  .contacts__header {
    font-size: 1.5em;
    margin-bottom: 10px;
    color: #004d40;
  }
  .contacts__container {
    list-style: none;
    padding: 0;
    display: inline-block;
  }
  .contacts__item {
    margin: 10px 0;
  }
  .contacts__title {
    font-weight: bold;
    margin-bottom: 5px;
  }
  .contacts__link {
    color: #00796b;
    text-decoration: none;
  }
  .contacts__link:hover {
    text-decoration: underline;
  }

  p {
    font-size: 1.2em;
    margin: 8px 0;
  }
  a {
    color: #00796b;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  hr {
    margin: 25px 0;
    border: none;
    height: 2px;
    background-color: #00796b;
  }
  .section {
    margin-bottom: 20px;
    /* Центрирование содержимого */
    display: flex;
    flex-direction: column;
    align-items: center;
  }
  h2 {
    margin-bottom: 10px;
    color: #004d40;
  }
  ul {
    list-style: none;
    padding: 0;
  }
  li {
    margin: 8px 0;
    font-size: 1.1em;
  }
  /* Стиль кнопки */
  .button {
    padding: 10px 20px;
    font-size: 1em;
    background-color: #00796b;
    color: #fff;
    border: none;
    border-radius: 8px;
    cursor: pointer;
    margin-top: 10px;
    transition: background-color 0.3s;
  }
  .button:hover {
    background-color: #004d40;
  }
</style>
</head>
<body>
<div class="container">
  <h1>Максим Тяпкин</h1>
  <img src="III.PNG" alt="III.PNG" class="photo" />

  <!-- Контакты -->
  <section class="contacts">
    <h2 class="contacts__header">Контакты</h2>
    <ul class="contacts__container">
      <li class="contacts__item">
        <p class="contacts__title">Эл. почта</p>
        <a class="contacts__link" href="mailto:maks.tyapkin.96@gmail.com">maks.tyapkin.96@gmail.com</a>
      </li>
      <li class="contacts__item">
        <p class="contacts__title">Instagram</p>
        <a class="contacts__link" href="https://instagram.com/MAXTYAPKIN" target="_blank">@MAXTYAPKIN</a>
      </li>
      <li class="contacts__item">
        <p class="contacts__title">VK</p>
        <a class="contacts__link" href="https://vk.com/id339648057" target="_blank">id339648057</a>
      </li>
    </ul>
  </section>

  <p>Город: Калуга</p>

  <hr />

  <!-- Профессиональные навыки -->
  <div class="section">
    <h2>Профессиональные навыки</h2>
    <button class="button" id="showSkillsBtn">Показать навыки</button>
    <ul id="skillsList" style="display: none;">
      <li><strong>Тестирование функциональности:</strong> проверка соответствия работы системы требованиям.</li>
      <li><strong>Работа с баг-трекерами:</strong> умение использовать Jira, GitHub для отслеживания ошибок.</li>
      <li><strong>Анализ требований:</strong> понимание бизнес-логики и требований к продукту.</li>
      <li><strong>Тест-планирование и документация:</strong> подготовка тест-кейсов, чек-листов и отчетов.</li>
      <li><strong>Автоматизация тестирования:</strong>навыки работы с автоматическими инструментами Postman и др.</li>
      <li><strong>Знание языков программирования:</strong> основы JavaScript, Python для автоматизации.</li>
  </div>

  <!-- Личные качества -->
  <div class="section">
    <h2>Личные качества</h2>
    <button class="button" id="showQualitiesBtn">Показать личные качества</button>
    <ul id="qualitiesList" style="display: none;">
      <li>Целеустремленный</li>
      <li>Пунктуальный</li>
      <li>Комуникабельный</li>
      <li>Инициативный</li>
      <li>Ответственный</li>
      <li>Внимательный к деталям</li>
      <li>Умею работать в команде</li>
    </ul>
  </div>

  <!-- Увлечения -->
  <div class="section">
    <h2>Увлечения</h2>
    <button class="button" id="showHobbiesBtn">Показать увлечения</button>
    <ul id="hobbiesList" style="display: none;">
      <li>Проводить время с семьей</li>
      <li>Футбол</li>
      <li>Автомобили</li>
      <li>Чтение книг</li>
      <li>Кулинария</li>
      <li>Рыбалка</li>
    </ul>
  </div>
</div>

<script>
  // Для увлечений
  const btnHobbies = document.getElementById('showHobbiesBtn');
  const hobbies = document.getElementById('hobbiesList');

  btnHobbies.addEventListener('click', () => {
    if (hobbies.style.display === 'none') {
      hobbies.style.display = 'block';
      btnHobbies.textContent = 'Скрыть увлечения';
    } else {
      hobbies.style.display = 'none';
      btnHobbies.textContent = 'Показать увлечения';
    }
  });

  // Для личных качеств
  const btnQualities = document.getElementById('showQualitiesBtn');
  const qualities = document.getElementById('qualitiesList');

  btnQualities.addEventListener('click', () => {
    if (qualities.style.display === 'none') {
      qualities.style.display = 'block';
      btnQualities.textContent = 'Скрыть личные качества';
    } else {
      qualities.style.display = 'none';
      btnQualities.textContent = 'Показать личные качества';
    }
  });

  // Для профессиональных навыков
  const btnSkills = document.getElementById('showSkillsBtn');
  const skills = document.getElementById('skillsList');

  btnSkills.addEventListener('click', () => {
    if (skills.style.display === 'none') {
      skills.style.display = 'block';
      btnSkills.textContent = 'Скрыть навыки';
    } else {
      skills.style.display = 'none';
      btnSkills.textContent = 'Показать навыки';
    }
  });
</script>
</body>
</html>