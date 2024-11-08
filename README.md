# sudoku838.github.io
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ежедневник</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f8f9fa;
        }
        h1 {
            text-align: center;
        }
        .entry {
            border: 1px solid #ccc;
            border-radius: 5px;
            padding: 10px;
            margin-bottom: 10px;
            background-color: #ffffff;
        }
        .date {
            font-weight: bold;
        }
    </style>
</head>
<body>
<h1>Ежедневник</h1>
<div class="entry">
    <div class="date">14 октября 2024</div>
    <p>Запись в ежедневник: встретиться с другом, купить билеты на поезд.</p>
</div>
<div class="entry">
    <div class="date">15 октября 2024</div>
    <p>Запись в ежедневник: сделать домашнее задание, подготовиться к встрече.</p>
</div>
<div class="entry">
    <div class="date">16 октября 2024</div>
    <p>Запись в ежедневник: прогуляться в парке, посетить выставку.</p>
</div>

</body>
</html>

<div id="tab1" class="tab-content active">
    <h2>Понедельник 14 октября 2024</h2>
</div>
<div id="tab2" class="tab-content">
    <h2>Вторник 15 октября 2024</h2>
</div>
<div id="tab3" class="tab-content">
    <h2>Среда 16 октяюря 2024</h2>
</div>

<script>
    function openTab(tabName) {
        var i, tabContent;
        tabContent = document.getElementsByClassName("tab-content");
        for (i = 0; i < tabContent.length; i++) {
            tabContent[i].style.display = "none";
        }
        document.getElementById(tabName).style.display = "block";
    }
</script>
.tabs {
  width: 100%;
  display: inline-block;
}
 
.tab-list {
  padding: 0;
  margin: 0;
  list-style: none;
}
 
.tab-item {
  display: inline-block;
  margin-right: 10px;
  padding: 10px;
  cursor: pointer;
  background-color: #f1f1f1;
  border-radius: 5px 5px 0 0;
}
 
.tab-item.active {
  background-color: #fff;
}
 
.tab-content {
  border: 1px solid #f1f1f1;
  padding: 20px;
  border-radius: 5px;
}
 
.tab-pane {
  display: none;
}
 
.tab-pane.active {
  display: block;
}
