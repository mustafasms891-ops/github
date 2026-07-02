<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>حراج العراق</title>

<style>
body{
    margin:0;
    font-family:Arial,sans-serif;
    background:#f5f5f5;
}
header{
    background:#0d6efd;
    color:white;
    padding:20px;
    text-align:center;
}
nav{
    background:white;
    padding:15px;
    text-align:center;
}
nav a{
    text-decoration:none;
    margin:10px;
    color:#0d6efd;
    font-weight:bold;
}
.search{
    text-align:center;
    margin:30px;
}
input{
    width:60%;
    padding:12px;
}
button{
    padding:12px 20px;
    background:#0d6efd;
    color:white;
    border:none;
}
.ads{
    display:flex;
    justify-content:center;
    gap:20px;
    flex-wrap:wrap;
}
.card{
    background:white;
    width:250px;
    padding:15px;
    border-radius:10px;
    box-shadow:0 0 10px #ccc;
}
</style>
</head>

<body>

<header>
<h1>حراج العراق</h1>
<p>بيع وشراء السيارات والعقارات والهواتف والوظائف</p>
</header>

<nav>
<a href="#">الرئيسية</a>
<a href="#">السيارات</a>
<a href="#">العقارات</a>
<a href="#">الهواتف</a>
<a href="#">الوظائف</a>
<a href="#">نشر إعلان</a>
</nav>

<div class="search">
<input type="text" placeholder="ابحث عن إعلان">
<button>بحث</button>
</div>

<div class="ads">

<div class="card">
<h3>سيارة للبيع</h3>
<p>تويوتا كورولا 2022</p>
</div>

<div class="card">
<h3>منزل للبيع</h3>
<p>منزل في بغداد</p>
</div>

<div class="card">
<h3>هاتف للبيع</h3>
<p>iPhone 15</p>
</div>

</div>

</body>
</html>
