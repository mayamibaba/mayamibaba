<input type="button"Авторезация
 value="" class="button">
<!DOCTYPE html> 
<html lang="uk">  
    <head> 
       <link rel="stylesheet" type="text/css" href="css/style.css">
       <title> Шкільна бібліотека </title>  
	  <meta charset="ANSI"> 
<script src="./time.js"></script>
    </head>
 <body> 
      <header> 
          <p class="stroke">Електронна бібліотека школи</p>
          <h2> «Бібліотека – це той храм, де завжди народжується і зберігається духовність. Пам’ятаймо, що у давнину бібліотеку називали «дім життя», «притулок мудрості», «аптека для душі» </h2>
       </header>
       <nav> 
          <ul> 
            <li><a href="index.html">Головна сторінка</a></li> 
            <li><a href="info.html">Про нас</a></li>
            <li><a href="gallery.html">Фотоальбом</a></li>
            <li><a href="form.html">Контакти</a></li>
          </ul>
       </nav>
     <p>Електронна бібліотека школи</p>  
<p>        </p>   
     
<button onclick="alert('Привіт! Так JS також працює')">Клікни на мене</button>
    <button onmouseover="alert('І це також працює')">Наведи на мене курсор</button>

     <footer> 
       <p>  Львів 2024 </p> 
<div id="clock"></div>
     </footer>
</body> 
</html>
<input type="button" value="Виклик" class="button">

<!DOCTYPE html>
<html lang="ua">
<head>
<title>Page Title</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
    box-sizing: border-box;
}

/* Стиль тіла  сторінки*/
body {
    font-family: Arial;
    margin: 0;
}

/* Заголовок/Логотип/Назва */
.header {
    padding: 80px;
    text-align: center;
    background: #1abc9c;
    color: white;
}

/* Збільшіть розмір шрифту заголовка */
.header h1 {
    font-size: 40px;
}

/* Стилізуйте верхню панель навігації */
.navbar {
    overflow: hidden;
    background-color: #333;
}
/* Стилізуйет посилання на панелі навігації */
.navbar a {
    float: left;
    display: block;
    color: white;
    text-align: center;
    padding: 14px 20px;
    text-decoration: none;
}

/* Посилання, вирівняне по правому краю */
.navbar a.right {
    float: right;
}

/* Змінити колір при наведенні курсора */
.navbar a:hover {
    background-color: #ddd;
    color: black;
}

/* Колонний контейнер */
.row {  
    display: -ms-flexbox; /* IE10 */
    display: flex;
    -ms-flex-wrap: wrap; /* IE10 */
    flex-wrap: wrap;
}

/* Створіть два нерівних стовпці, які сидять один біля одного */
/* Бічна панель/ліва колонка */
.side {
    -ms-flex: 30%; /* IE10 */
    flex: 30%;
    background-color: #f1f1f1;
    padding: 20px;
}
/* Основна колонка */
.main {   
    -ms-flex: 70%; /* IE10 */
    flex: 70%;
    background-color: white;
    padding: 20px;
}

/* Фальшиве зображення, тільки для цього прикладу */
.fakeimg {
    background-color: #aaa;
    width: 100%;
    padding: 20px;
}

/* Нижній колонтитул */
.footer {
    padding: 20px;
    text-align: center;
    background: #ddd;
}

/* Адаптивний макет – коли ширина екрана менше 700 пікселів, накладіть два стовпці один на одного, а не поруч. */
@media screen and (max-width: 700px) {
    .row {   
        flex-direction: column;
    }
}

/* Адаптивний макет – коли екран має ширину менше 400 пікселів, накладайте навігаційні посилання один на одного, а не поруч. */
@media screen and (max-width: 400px) {
    .navbar a {
        float: none;
        width: 100%;
    }
}
</style>
</head>
<body>

<div class="header">
  <h1> Мій веб-сайт </h1>
  <p> Сайт, створений мною.</p>
</div>

<div class="navbar">
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#">Link</a>
  <a href="#" class="right">Link</a>
</div>
<div class="row">
  <div class="side">
      <h2>Про мене</h2>
      <h5> Моє фото:</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p> Якийсь текст про мене..</p>
      <h3> Більше тексту </h3>
      <p>Опис тексту до зображень.</p>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div><br>
      <div class="fakeimg" style="height:60px;">Image</div>
  </div>
  <div class="main">
      <h2>Назва Заголовка </h2>
      <h5> Опис заголовка, Листопад 15, 2023</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Якийсь текст.</p>
      <p>Чи був у нас Дід Мороз?
Вважається, що у кожній країні є свій аналог Діда Мороза. Десь Санта Клаус, десь Пер Ноель, а десь — Мікулаш. Але це твердження хибне. Адже в Україні не існувало на Новий Рік святкового дідуся, який приходив і дарував подарунки чемним дітям. Така традиція існувала на День Святого Миколая 19 грудня, і герой був не казковим, а реальним, що жив колись на землі. Уособлював він зовсім інші ідеї та не асоціювався з Новим Роком.

Так само, без відношення до свят — існував Морозко, сивий та добрий дід, який символізує зиму.</p>
      <br>
      <h2>Назва заголовка</h2>
      <h5> Опис заголовка, Січень 15 2022 р</h5>
      <div class="fakeimg" style="height:200px;">Image</div>
      <p>Якийсь текст</p>
      <p>Чи була у нас ялинка?
Ні, був солом’яний сніп, який назвали Дідухом. Він уособлював спільного предка, рід, зв’язок між поколіннями. Але його, як і ялинку, прикрашали, тож ця традиція залишилась незмінною..</p>
  </div>
</div>
<div class="footer">
  <h2> Нижній колонтитул </h2>
      <p>Хто розробник/Контакти/Можна задати лого</p>
      <p>2023 © Використання матеріалів сайту лише при наявності гіперпосилання</p>
</div>

</body>
</html>

