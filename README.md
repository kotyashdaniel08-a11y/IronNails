# IronNails<!DOCTYPE html>
<html lang="uk">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Luxury Nails Studio</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#fff8fb;
color:#333;
}

header{
background:linear-gradient(135deg,#ff69b4,#ffb6c1);
color:white;
text-align:center;
padding:80px 20px;
}

header h1{
font-size:48px;
margin-bottom:15px;
}

header p{
font-size:20px;
}

.btn{
display:inline-block;
margin-top:20px;
padding:15px 30px;
background:white;
color:#ff1493;
text-decoration:none;
border-radius:50px;
font-weight:bold;
}

nav{
display:flex;
justify-content:center;
gap:30px;
padding:20px;
background:white;
position:sticky;
top:0;
z-index:999;
box-shadow:0 2px 10px rgba(0,0,0,.1);
}

nav a{
text-decoration:none;
color:#ff1493;
font-weight:bold;
}

section{
padding:60px 20px;
max-width:1200px;
margin:auto;
}

h2{
text-align:center;
margin-bottom:40px;
color:#ff1493;
}

.services{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
text-align:center;
}

.price{
font-size:24px;
color:#ff1493;
font-weight:bold;
margin-top:10px;
}

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery img{
width:100%;
height:300px;
object-fit:cover;
border-radius:20px;
}

.reviews{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.review{
background:white;
padding:20px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.booking{
background:white;
padding:30px;
border-radius:20px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
max-width:800px;
margin:auto;
}

.booking form{
display:flex;
flex-direction:column;
gap:15px;
}

input,
select,
textarea{
padding:12px;
border:1px solid #ddd;
border-radius:10px;
font-size:16px;
}

button{
background:#ff1493;
color:white;
border:none;
padding:15px;
font-size:18px;
border-radius:10px;
cursor:pointer;
}

button:hover{
background:#e60073;
}

footer{
background:#ff69b4;
color:white;
text-align:center;
padding:30px;
margin-top:50px;
}

</style>
</head>
<body>

<header>
<h1>Luxury Nails Studio</h1>
<p>Професійний манікюр та педикюр преміум-класу</p>
<a href="#booking" class="btn">Записатися онлайн</a>
</header>

<nav>
<a href="#services">Послуги</a>
<a href="#gallery">Галерея</a>
<a href="#reviews">Відгуки</a>
<a href="#booking">Запис</a>
<a href="#contacts">Контакти</a>
</nav>

<section id="services">

<h2>Наші послуги</h2>

<div class="services">

<div class="card">
<h3>Манікюр</h3>
<p>Комбінований манікюр</p>
<div class="price">80 zł</div>
</div>

<div class="card">
<h3>Гель-лак</h3>
<p>Покриття + зміцнення</p>
<div class="price">120 zł</div>
</div>

<div class="card">
<h3>Нарощування</h3>
<p>Гель, будь-яка довжина</p>
<div class="price">180 zł</div>
</div>

<div class="card">
<h3>Педикюр</h3>
<p>Повний догляд</p>
<div class="price">150 zł</div>
</div>

</div>

</section>

<section id="gallery">

<h2>Наші роботи</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1604654894610-df63bc536371?w=800" alt="">
<img src="https://images.unsplash.com/photo-1519014816548-bf5fe059798b?w=800" alt="">
<img src="https://images.unsplash.com/photo-1610992015732-2449b76344bc?w=800" alt="">

</div>

</section>

<section id="reviews">

<h2>Відгуки клієнтів</h2>

<div class="reviews">

<div class="review">
★★★★★
<p>Дуже якісний сервіс та красивий манікюр!</p>
<b>Анна</b>
</div>

<div class="review">
★★★★★
<p>Найкраща студія в місті ❤️</p>
<b>Олена</b>
</div>

<div class="review">
★★★★★
<p>Стерильно, швидко та професійно.</p>
<b>Марія</b>
</div>

</div>

</section>

<section id="booking">

<h2>Онлайн запис</h2>

<div class="booking">

<form id="bookingForm">

<input
type="text"
placeholder="Ваше ім'я"
required>

<input
type="tel"
placeholder="Телефон"
required>

<select required>
<option value="">Оберіть послугу</option>
<option>Манікюр</option>
<option>Гель-лак</option>
<option>Нарощування</option>
<option>Педикюр</option>
</select>

<select required>
<option value="">Оберіть майстра</option>
<option>Оксана</option>
<option>Юлія</option>
<option>Катерина</option>
</select>

<input type="date" required>

<select required>
<option>09:00</option>
<option>10:00</option>
<option>11:00</option>
<option>12:00</option>
<option>13:00</option>
<option>14:00</option>
<option>15:00</option>
<option>16:00</option>
<option>17:00</option>
<option>18:00</option>
</select>

<textarea
rows="4"
placeholder="Коментар"></textarea>

<button type="submit">
Підтвердити запис
</button>

</form>

</div>

</section>

<section id="contacts">

<h2>Контакти</h2>

<p style="text-align:center;font-size:18px;">
📞 +48 123 456 789<br><br>
📍 Radzyń Podlaski, Polska<br><br>
📸 Instagram: @luxury_nails_studio
</p>

</section>

<footer>

<h3>Luxury Nails Studio</h3>
<p>© 2026 Усі права захищені</p>

</footer>

<script>

document
.getElementById('bookingForm')
.addEventListener('submit', function(e){

e.preventDefault();

alert(
'Дякуємо! Ваш запис успішно створено. Наш адміністратор зв’яжеться з вами.'
);

this.reset();

});

</script>

</body>
</html>

