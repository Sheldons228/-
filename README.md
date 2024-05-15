	(ФАЙЛ "index.html")

<!DOCTYPE html>
<html lang="en">  
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Главная страница</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" href="logo.png">
  </head>
  <body>
    <nav>
      <div class="logo"><img src="logo.png"></div>
      <ul>
        <li>Главная страница</li>
        <li><a href="about.html">О нас</a></li>
        <li><a href="products.html">Продукция</a></li>
        <li><a href="contacts.html">Контакты</a></li>
      </ul>
    </nav>
    <div class="container">
      <span class="text1"><h1>Добро пожаловать на сайт</h1></span>
      <span class="text2">компании ООО"Колос"</span>
    </div>
  </body>
</html>


	(ФАЙЛ "style.css")

* {
    margin: 0;
    padding: 0;
}
    
body { 
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(background.jpg);
    background-size:cover;          
}
    
a {
    text-decoration: none;
}
    
nav {
    width: 100vw;  
    display: flex;
    background: rgba(0, 0, 0, 0.7);    
}
    
.logo {
    margin-top: 2vh;
    font-size: 25px;
    width: 5vw;
    margin-left: 5vw;
}
    
ul {
    margin-top: 6.5vh;
    width: 55vw;
    height: 3.5vh;
    text-align: center;
    margin-left: 35vw;
}
    
ul li {
    display: inline-block;
    cursor: pointer;
    font-size: 25px;
    margin-left: 2vw;
    margin-right: 2vw;
    color: wheat;
}
 
ul li a {
    text-decoration: none;
    color: wheat;
    background: linear-gradient(orange 0 0) bottom /var(--t, 0) 2px no-repeat;
    transition: .5s;
}
  
ul li:hover {
    color: wheat;
    transition: 0.3s;
    color: white;
    --t: 100%;
}

.container {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    width: 100%;
}

.container span {
    text-transform: uppercase;
    display: block;
}

.text1 {
    color: rgb(253, 222, 85);
    font-size: 30px;
    font-weight: 700;
    letter-spacing: 20px;
    margin-bottom: 20px;
    animation: text 3s 1;
}

@keyframes text {
    0%{
        color: black;
        margin-bottom: -10px;
    }
    30%{
        letter-spacing: 25px;
        margin-bottom: 20px;
    }
    85%{
        letter-spacing: 8px;
        margin-bottom: 20px;
    }
}

.text2{
    font-size: 25px;
    color: rgb(120, 252, 120);
    animation: text 3s 1;
}


	(ФАЙЛ "about.html")

<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>О нас</title>
    <link rel="stylesheet" href="about.css">
    <link rel="icon" href="logo.png">
  </head>

  <body>
    <nav>
      <div class="logo"><a href="index.html"><img src="logo.png"></a></div>
      <ul>
        <li><a href="index.html">Главная страница</a></li>
        <li>О нас</li>
        <li><a href="products.html">Продукция</a></li>
        <li><a href="contacts.html">Контакты</a></li>
      </ul>
    </nav>
  
    <main>
      <div class="media">
        <center><h1>Наша компания, ООО «Колос», 
        использует только лучшую технику, 
        чтобы обеспечить высокое качество 
        нашей продукции и удовлетворить
        потребности наших клиентов.</h1></center>
      </div>
    </main>

    <div class="text">
      <div class="img_1"><img src="seed.png" style="float: right"></div>
      <h2>Немного о нас</h2><br>
      <h3>Компания ООО"Колос" в основном занимается выращиванием зерновых культур. 
        Помимо этого выращиванием зернобобовых культур, семян масличных культур, овощей, 
        столовых корнеплодных и клубнеплодных культур с высоким содержанием крахмала или инулина, 
        сахарной свеклы, оптовой торговлей зерном, масличными семенами и маслосодержащими плодами, 
        свежим картофелем, прочими свежими овощами, свежими фруктами и орехами.</h3><br>
      <h3>Наша компания тщательно следит как за выращиванием культур, так и за их хранением, 
        и делает всё возможное чтобы они были лучшего качества и всегда оставались в хорошем состоянии. 
        Выращенный товар, в соответствии требованиям, хранится в определённых условиях, температуре, 
        и периодически проверяется на качество.</h3><br>
      <h3>Компания появилась 1 ноября 1999 года, и уже более 25-ти лет радует заказчиков отличным качеством товара.</h3>
    </div>

    <footer class="footer"><hr><br>   
      <div class="img_2"><img src="logo.png">
        <h4>Вся наша продукция производится с использованием передовых технологий 
         и с соблюдением высоких стандартов качества и безопасности.</h4>        
      </div> 
      <div class="inform">
        <h6>Адрес: </h6>
        <h5>Ставропольский край, Изобильненский район, г. Изобильный, ул. Совхозная, д. 1</h5><br>       
        <h6>Номер: </h6>
        <h5>&nbsp;+7 865 452-38-41</h5><br>        
        <h6>Эл. почта: </h6>
        <h5>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kolos2004@rambler.ru</h5>
      </div> 
      <div class="verticalLine"></div>
      <div class="gorisontLine"><hr><div>
      <div style="margin-left: 150px; margin-top: 35px;">
        <h5>© ООО"КОЛОС"</h5>
      </div>
    </footer>
  </body>
</html>


	(ФАЙЛ "about.css")

* {
    margin: 0;
    padding: 0;
}

body { 
    background: rgb(221, 220, 220);
    background-size:cover;
}

a {
    text-decoration: none;
}

nav {
    width: 100vw;  
    display: flex;
    background: rgba(0, 0, 0, 0.7);
    position: fixed;
}

.logo {
    margin-top: 2vh;
    font-size: 25px;
    width: 5vw;
    margin-left: 5vw;
}

ul {
    margin-top: 6.5vh;
    width: 55vw;
    height: 3.5vh;
    text-align: center;
    margin-left: 35vw;
}

ul li {
    display: inline-block;
    cursor: pointer;
    font-size: 25px;
    margin-left: 2vw;
    margin-right: 2vw;
    color: wheat;
}

ul li a {
    text-decoration: none;
    color: wheat;
    background: linear-gradient(orange 0 0) bottom /var(--t, 0) 2px no-repeat;
    transition: .5s;
}

ul li:hover {
    color: wheat;
    transition: 0.3s;
    color: white;
    --t: 100%;
}

main {
    background: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(1.png) no-repeat;
    display: flex;
    width: 100ph;
    height: 35vh;
    margin-top: 5ph;
}

.media {
    width: 55vw;
    margin-left: 400px;
}

h1 {   
    font-size: 40px;
    color: white;
    margin-top: 140px;
    text-shadow: 4px 4px 6px black;
}

.text {
    width: 40vw;
    margin-left: 200px;   
}

.img_1 {
    width: 70vw;
}

h2 {
    font-size: 40px;
    margin-top: 20px;
}    

.footer {
    background: rgb(206, 206, 206);
    margin-top: 170px;
    height: 240px;
}

.img_2 {
    margin-left: 200px;
    margin-top: 20px;
}

h4 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 150px;
    width: 20vw;
    margin-top: -100px;
}

h5 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 60px;
    width: 30vw;
    margin-top: -18px;
}

h6 {
    color: black;
    font-size: 18px;
}

.inform {
    margin-left: 800px;
    width: 30vw;
    margin-top: -55px;
}

.verticalLine {
    border-left: 1px solid rgb(175, 175, 175);
    height: 188px;
    margin-left: 750px;
    margin-top: -146px;
}


	(ФАЙЛ "products.html")

<!DOCTYPE html>
<html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Продукция</title>
        <link rel="stylesheet" href="products.css">
        <link rel="icon" href="logo.png">
    </head>
    
    <body>
        <nav>
            <div class="logo"><a href="index.html"><img src="logo.png"></a></div>
            <ul>
                <li><a href="index.html">Главная страница</a></li>
                <li><a href="about.html">О нас</a></li>
                <li>Продукция</li>
                <li><a href="contacts.html">Контакты</a></li>
            </ul>
        </nav>
    </body>

    <main>   
        <div class="img_1"><img src="product.jpg" style="float: right"></div>
        <h1>Мы гордимся предлагать вам широкий ассортимент <br>
        высококачественной продукции.</h1>
    </main>
    <main>
        <h3>Сезонные специальности<br>
            Мы также рады представить вам сезонные специальности, которые разнообразят ваше меню и подарят новые вкусовые ощущения.</h3>
    </main>

    <footer class="footer"><hr><br>
        <div class="img_2"><img src="logo.png">
            <h4>Вся наша продукция производится с использованием передовых технологий 
            и с соблюдением высоких стандартов качества и безопасности.</h4>
        </div>
        <div class="inform">
            <h6>Адрес: </h6>
            <h5>Ставропольский край, Изобильненский район, г. Изобильный, ул. Совхозная, д. 1</h5><br>
            <h6>Номер: </h6>
            <h5>&nbsp;+7 865 452-38-41</h5><br>
            <h6>Эл. почта: </h6>
            <h5>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kolos2004@rambler.ru</h5>
        </div>
        <div class="verticalLine"></div>
        <div class="gorisontLine"><hr><div>
        <div style="margin-left: 150px; margin-top: 35px;">
            <h5>© ООО"КОЛОС"</h5>
        </div>
    </footer>
</html>


	(ФАЙЛ "products.css")

* {
    margin: 0;
    padding: 0;
}

body { 
    background: rgb(221, 220, 220);
    background-size:cover;
}

a {
    text-decoration: none;
}

nav {
    width: 100vw;  
    display: flex;
    background: rgba(0, 0, 0, 0.7);
    position: fixed;
}

.logo {
    margin-top: 2vh;
    font-size: 25px;
    width: 5vw;
    margin-left: 5vw;
}

ul {
    margin-top: 6.5vh;
    width: 55vw;
    height: 3.5vh;
    text-align: center;
    margin-left: 35vw;
}

ul li {
    display: inline-block;
    cursor: pointer;
    font-size: 25px;
    margin-left: 2vw;
    margin-right: 2vw;
    color: wheat;
}

ul li a {
    text-decoration: none;
    color: wheat;
    background: linear-gradient(orange 0 0) bottom /var(--t, 0) 2px no-repeat;
    transition: .5s;
}

ul li:hover {
    color: wheat;
    transition: 0.3s;
    color: white;
    --t: 100%;
}

main {
    display: flex;
    width: 100ph;
    height: 35vh;
    margin-top: 5ph;
}

.media {
    width: 55vw;
    margin-left: 400px;
}

.text {
    width: 40vw;
    margin-left: 200px;   
}

h1 {
    font-size: 30px;
    margin-top: 140px;
}

h2 {
    font-size: 40px;
    margin-top: 20px;
}

.footer {
    background: rgb(206, 206, 206);
    margin-top: 360px;
    height: 250px;
}

.img_1 {
    
    margin-top: 13%;
    width: 35vw;
}

.img_2 {
    margin-left: 200px;
    margin-top: 20px;
}

h4 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 150px;
    width: 20vw;
    margin-top: -100px;
}

h5 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 60px;
    width: 30vw;
    margin-top: -18px;
}

h6 {
    color: black;
    font-size: 18px;
}

.inform {
    margin-left: 800px;
    width: 30vw;
    margin-top: -55px;
}

.verticalLine {
    border-left: 1px solid rgb(175, 175, 175);
    height: 188px;
    margin-left: 750px;
    margin-top: -146px;
}


	(ФАЙЛ "contacts.html")

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Контакты</title>
    <link rel="stylesheet" href="contacts.css">
    <link rel="icon" href="logo.png">
  </head>

  <body>
    <nav>
      <div class="logo"><a href="index.html"><img src="logo.png"></div>
        <ul>
          <li><a href="index.html">Главная страница</a></li>
          <li><a href="about.html">О нас</a></li>
          <li><a href="products.html">Продукция</a></li>
          <li>Контакты</li>
        </ul>
      </div>
    </nav>    
  </body>

  <div class="text">
    <h2>Наши контакты: </h2><br>
    <hr style="margin-right: 200px;"><br>
    <h1>Наш адрес: </h1><br></br>
    <h3>Ставропольский край, Изобильненский район, г. Изобильный, ул. Совхозная, д. 1.</h3>

    <div style="margin-left: 300px; margin-top: -123px;">
      <h1>Эл. почта: </h1><br></br>
      <h3>kolos2004@rambler.ru</h3><br>
      <h1>Телефон: </h1><br></br>
      <h3>+7 865 452-38-41</h3>
    </div>
  </div>    

  <div class="map">
    <script type="text/javascript" charset="utf-8" 
    async src="https://api-maps.yandex.ru/services/constructor/1.0/js/?um=constructor%3Af2252e491f7ff9f4b3f6c762b5ce5a2be58db92352f858fc8c2410bb2f554be3&amp;width=786&amp;height=461&amp;lang=ru_RU&amp;scroll=true"></script>
  </div>   

  <footer class="footer"><hr><br>   
    <div class="img_2"><img src="logo.png">
      <h4>Вся наша продукция производится с использованием передовых технологий 
       и с соблюдением высоких стандартов качества и безопасности.</h4>        
    </div> 
    <div class="inform">
      <h6>Адрес: </h6>
      <h5>Ставропольский край, Изобильненский район, г. Изобильный, ул. Совхозная, д. 1</h5><br>       
      <h6>Номер: </h6>
      <h5>&nbsp;+7 865 452-38-41</h5><br>        
      <h6>Эл. почта: </h6>
      <h5>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;kolos2004@rambler.ru</h5>
    </div> 
    <div class="verticalLine"></div>
    <div class="gorisontLine"><hr><div>
    <div style="margin-left: 150px; margin-top: 35px;">
      <h5>© ООО"КОЛОС"</h5>
    </div>
  </footer>  
</html>


	(ФАЙЛ "contacts.css")

* {
    margin: 0;
    padding: 0;
}

body { 
    background: rgb(221, 220, 220);
    background-size:cover;        
}

a {
    text-decoration: none;
}

nav {
    width: 100vw;  
    display: flex;
    background: rgba(0, 0, 0, 0.8);
}

.logo {
    margin-top: 2vh;
    font-size: 25px;
    width: 5vw;
    margin-left: 5vw;
}

ul {
    margin-top: 6.5vh;
    width: 55vw;
    height: 3.5vh;
    text-align: center;
    margin-left: 35vw;
}

ul li {
    display: inline-block;
    cursor: pointer;
    font-size: 25px;
    margin-left: 2vw;
    margin-right: 2vw;
    color: wheat;
}

ul li a {
    text-decoration: none;
    color: wheat;
    background: linear-gradient(orange 0 0) bottom /var(--t, 0) 2px no-repeat;
    transition: .5s;
}

ul li:hover {
    color: wheat;
    transition: 0.3s;
    color: white;
    --t: 100%;
}

.text {
    width: 40vw;
    margin-left: 200px;   
}

h1 {
    font-size: 23px;
    width: 20vw;
}

h2 {
    font-size: 30px;
    margin-top: 40px;
}

h3 {
    color: rgb(68, 68, 68);
    font-size: 16.6px;
    width: 10vw;
    margin-top: -18px;
}

.map {
    margin-top: -207px;
    margin-left: 45%;
}

.footer {
    background: rgb(206, 206, 206);
    margin-top: 75px;
    height: 240px;
}

.img_2 {
    margin-left: 200px;
    margin-top: 20px;
}

h4 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 150px;
    width: 20vw;
    margin-top: -100px;
}

h5 {
    color: rgb(77, 77, 77);
    font-size: 15px;
    margin-left: 60px;
    width: 30vw;
    margin-top: -18px;
}

h6 {
    color: black;
    font-size: 18px;
}

.inform {
    margin-left: 800px;
    width: 30vw;
    margin-top: -55px;
}

.verticalLine {
    border-left: 1px solid rgb(175, 175, 175);
    height: 188px;
    margin-left: 750px;
    margin-top: -146px;
}