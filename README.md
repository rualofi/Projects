<div id="header" align="center">
        <h1>Привет! Меня зовут Аполлинария!</h1>
        <h3>Я начинающий Data Scientist. Занимаюсь параллельным изучением экономики, финансов и технологий Data Science.</h3>
    </div>
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>Мои проекты</title>
    <style>
        table {
            border-collapse: collapse;
        }
        td {
            padding: 10px;
            position: relative;
        }
        td::before {
            content: "🌸";
            position: absolute;
            top: -15px;
            left: 50%;
            transform: translateX(-50%);
        }
        td::after {
            content: "🌸";
            position: absolute;
            bottom: -15px;
            left: 50%;
            transform: translateX(-50%);
        }
        td:first-child::before, td:first-child::after {
            left: -15px;
            top: 50%;
            transform: translateY(-50%);
        }
        td:last-child::before, td:last-child::after {
            right: -15px;
            top: 50%;
            transform: translateY(-50%);
        }
    </style>
</head>
<body>
    <table>
        <tr>
            <td><a href="https://github.com/rualofi/Projects/edit/main/README.md">Ссылка на проект</a></td>
            <td>Это мой первый проект, в котором приведена аналитика по списку школьников и сделаны выводы о влияющих и некоррелирующих факторах</td>
        </tr>
    </table>
</body>
</html>
