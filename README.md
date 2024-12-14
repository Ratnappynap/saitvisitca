<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="CSS/style.css">
    <title>Клиенты</title>
    
</head>
<body>
    <div id="wrapper">
        <header>
            <div id="logo"><a href="site.html"><span class="pink">Сайт</span> <span class="greem"><i>визитка</i></span></a></div>
            <ul>
        <li><a href="uslugi.html">услуги</a></li>
        <li><a href="onas.html">о нас</a></li>
        <li><a href="client.html">клиенты</a></li>
        <li><a href="contacti.html">контакты</a></li>
        
            </ul>
        </header>
<main class="clienti">

<img src="https://www.aces.edu/wp-content/uploads/2023/04/iStock-1232014586.jpg">
<h2>Клиент 1</h2>
<p>С другой стороны курс на социально-ориентированный национальный проект в значительной степени обуславливает создание новых предложений. Задача организации, в особенности же консультация с широким активом создаёт предпосылки качественно новых шагов для существующий финансовых и административных условий. Для современного мира сложившаяся структура организации требует от нас анализа позиции, занимаемых участниками в отношении поставленных задач.</p><br>
<img src="https://img.freepik.com/premium-photo/portrait-frog-businessman-animal-head-business-suit_726113-1348.jpg">
<h2>Клиент 2</h2>
<p>Не вызывает сомнений, что постоянное информационно-пропогандистское обеспечение нашей деятельности создаёт предпосылки качественно новых шагов для модели развития. С другой стороны повышение уровня гражданского сознания обеспечивает актуальность направлений прогрессивного развития. Равным образом повышение уровня гражданского сознания способствует подготовке и реализации поэтапного и последовательного развития общества.</p><br>
<img src="https://cdn.mos.cms.futurecdn.net/39CUYMP8vJqHAYGVzUghBX.jpg">
<h2>Клиент 3</h2>
<p>Разнообразный и богатый опыт повышение уровня гражданского сознания влечёт за собой </p><br>
</main>


</div>
<footer class="for-footer">
    <a href="form.html"><p class="footer_block">Написать нам &#9650;</p></a>
   <p class="footer_block"> &copy; Новая компания</p>
   <div class="footer_icons">
       <a  href="#" target="_blank"><img class="footer_img" src="img/ok.png"alt=""></a>
        <img class="footer_img" src="img/vk.png"alt="">
        <img class="footer_img" src="img/mailru.png"alt="">
    </div>
    * {
    margin:0;
    padding: 0;
}
html,body {
  height: 100%;
  background-color: rgba(57, 173, 57, 0.178);
color: rgb(73, 99, 3);
}
header, main, footer {
    border: black solid none;
    width: 1040px;
    margin: 0 auto;
    float: flex;
    
}
#wrapper{
    min-height: 100%;
    height: auto;
    height: 100%;
     width: 100%;

}
#wrapper a{
    min-height: 100%;
    height: auto;
    height: 100%;
     width: 100%;
text-decoration: none;
color: darkolivegreen;
text-transform: uppercase;
font-weight: bold;
}
header li{
    display: inline;
    margin-top: 10px;
    padding: 10px;
    font-size: 20px;
    text-decoration: none;
}
header ul{
list-style: none;
margin: 0px;
padding-left: 10px;
padding-top: 39px;
text-decoration: none;
}
#logo {

    
    font-weight: bold;
    line-height: 50px;
    font-size: 24px;
    float: left;
    margin-right: 100px;
   
}
header{
    height:120px; 
    text-transform: uppercase;   
}
main{
    padding-bottom: 100px;
    text-align: center;
}
footer{   
    margin-top: 20px;
    margin: -100px auto 0;
    position: relative;
    height: 100px;
}
.main_img-float{
    width: 550px;
margin-right: 40px;
float: left;

}

#panorama{
    width: 100%;
    height: 150px;
    background: url(../img/2.jpg) no-repeat 70%;
    background-size: cover; 
}

.services_img{
 width: 240px;
}

.services_item{
   margin-right: 40px;
   margin-left: 40px;
max-width: 240px;
float: left;
margin-top: 10px;
   }
 
.services{
    margin: 35 px;
    border: 5px solid none;
}
.clearfix::after{
    content: "";
    display: table;
    clear: both;
}
.h1--invisible{
    visibility: hidden;
}
.for-main{
   border: 4px solid none;
   margin: -100 auto 0;
    height: 300px;
    width: 550px;
text-align: center;

}
.main_img-float2{
    width: 550px;
margin: 0px;
float: flex;

}


.datiyzhe{
  text-align: center;
    text-transform: uppercase;
    border: 5px solid  none;
}

.for-footer{
text-transform: uppercase;

}

.contactiinfo{
    text-align: center;
    
    border: 5px solid  none;
    padding: 3px;
}
.contactiinfo h2{
    text-align: center;
    text-transform: uppercase;
    border: 5px solid  none;
    padding: 3px;
}

.contactiinfo p{
    text-align: center;
    color: green;
    padding: 2px;
}
.contactiinfo a{
    text-align: center;
    color: green;
    padding: 2px;
}
#logo a{
    text-transform: uppercase;
    text-decoration: none;
    color: white;
    font-weight: bold;
    line-height: 100px;
    font-size: 24px;

}
.pink{
    color: rgb(1, 61, 1);
    
}
.greem{
    color:darkolivegreen;
}
.for-footer a:hover{
    color: rgb(2, 61, 2);
}
.for-footer a{
    color: green;
}
.footer_block, .footer_icons {
    margin-top: 15px;
    display: inline-block;
    width: 335px;
    font-style: oblique;
    border: 4px solid none;
}


.footer_icons{
    text-align: right;
border: 4px solid none;
}
.footer_img{
    width: 40px;
    margin-left: 10px;
padding-top: 10px;
   
}
h1, h2{
    text-transform: uppercase;
    font-weight: bold;
    font-size: 20px;
}
.services a{
    text-decoration: none;
    color: darkgreen;
}
table{
border: 4px solid rgba(30, 92, 5, 0.527);
border-collapse: collapse;
text-align: center;
width: 900px;
margin-left: 30px;
}
td, th {
border: 2px solid rgba(66, 185, 10, 0.534);
text-align: center;
padding: 10px;
}
.price th:first-child{
 width: 10%;
 
}
.price th:nth-child(2), .price th:first-child{
    width: 25%;
    
}
.price tr:nth-child(2){
    width: 25%;
    background-color: rgba(78, 184, 29, 0.274);
}
.price tr:nth-child(4){
    width: 25%;
    background-color: rgba(78, 184, 29, 0.274);
}
textarea{
    color: rgba(19, 58, 14, 0.493);
    text-align: left;
    background-color: rgba(141, 219, 62, 0.192);
    border:2px solid darkgreen;
    width: 300px;
    height: 230px;
}
label{
    padding-right: 10px;
}
input{
    background-color: rgba(141, 219, 62, 0.192);
    color:rgba(19, 58, 14, 0.493) ; 
    border:2px solid darkgreen;
    width: 270px;
}
input[type="submit"]{
    background-color: rgba(216, 255, 194, 0.562);
    border:2px solid darkgreen;
    width: 200px;
    height: 300;
}
option{
    background-color: rgba(141, 219, 62, 0.192);
    color:rgba(19, 58, 14, 0.493) ;
    border:2px solid darkgreen;
    width: 270px;
}
#topic{
    background-color: rgba(141, 219, 62, 0.192);
    color:rgba(19, 58, 14, 0.493) ;
     border:2px solid darkgreen; 
     width: 270px;
}

#contact-form{
    height: 20px;
     width: 250px;
    padding-left: 5px;
    text-align: left;
 margin-bottom: 10px;
  font-size: 20px;
  font-family: 'Times New Roman', Times, serif;
}
#contact-form input[type="submit"]:hover{
    background-color: rgba(179, 248, 60, 0.568);
}
#contact-form input[type="text"]:hover{
    background-color: rgba(179, 248, 60, 0.568);
}
.clienti img{
    width: 240px;
float: left;
padding: 10px;
}
.clienti {
text-align: center;
float: auto;;

}

</footer>

</body>
</html>
