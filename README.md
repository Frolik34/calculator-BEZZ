# calculator-BEZZ
Калькулятор артефактов BEZZ 
<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8" />
<title>Калькулятор артефактов сталкера</title>
<style>
  body { font-family: Arial, sans-serif; margin: 20px; }
  table { border-collapse: collapse; width: 100%; margin-bottom: 20px; }
  th, td { border: 1px solid #ccc; padding: 8px; text-align: center; }
  th { background-color: #f4f4f4; }
  .total { font-weight: bold; font-size: 1.2em; }
</style>
</head>
<body>

<h2>Выберите артефакты</h2>
<table id="artifactsTable">
  <thead>
    <tr>
      <th>Выбор</th>
      <th>Название</th>
      <th>Эффект</th>
      <th>Радиус (м)</th>
      <th>Восстановление здоровья</th>
      <th>Восстановление энергии</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><input type="checkbox" onchange="calculate()"></td>
      <td>Артефакт 1</td>
      <td>+10 к здоровью</td>
      <td>2</td>
      <td>5</td>
      <td>3</td>
    </tr>
    <tr>
      <td><input type="checkbox" onchange="calculate()"></td>
      <td>Артефакт 2</td>
      <td>+15 к энергии</td>
      <td>1.5</td>
      <td>2</td>
      <td>7</td>
    </tr>
    <!-- Добавьте свои артефакты сюда -->
  </tbody>
</table>

<h3>Итоговые эффекты</h3>
<p class="total">Общее восстановление здоровья: <span id="totalHealth">0</span></p>
<p class="total">Общее восстановление энергии: <span id="
