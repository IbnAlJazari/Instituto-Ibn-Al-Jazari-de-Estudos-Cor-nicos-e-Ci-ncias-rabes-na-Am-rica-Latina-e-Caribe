/* إعدادات عامة للصفحة */
body {
  font-family: 'Tahoma', sans-serif;
  margin: 0;
  padding: 0;
  background-color: #fff;
  color: #333;
}

/* رأس الصفحة */
header {
  background-color: #004d00; /* أخضر داكن */
  color: #fff;
  padding: 20px;
  text-align: center;
}
header .logo h1 {
  margin: 0;
  font-size: 2em;
}

/* قائمة التنقل */
nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 10px 0;
}
nav ul li {
  margin: 0 10px;
}
nav ul li a {
  color: #fff;
  text-decoration: none;
}

/* زر تغيير اللغة */
.language-switch {
  margin-top: 10px;
}
.language-switch a {
  color: #fff;
  text-decoration: none;
  margin: 0 5px;
}

/* قسم البانر الرئيسي */
main .hero {
  display: flex;
  flex-wrap: wrap;
  background: url('background-pattern.jpg') repeat; /* يمكن استخدام نمط زخرفة إسلامية هنا */
  padding: 20px;
  align-items: center;
  justify-content: center;
}
.hero-content {
  max-width: 600px;
  padding: 20px;
}
.hero-content h2 {
  font-size: 1.8em;
  margin: 0 0 10px;
}
.hero-content p {
  font-size: 1.2em;
}
.hero-image img {
  max-width: 100%;
  height: auto;
  border: 3px solid #d4af37;  /* ذهبي */
}

/* قسم الروابط السريعة للأقسام */
.sections {
  display: flex;
  flex-wrap: wrap;
  margin: 20px;
  justify-content: center;
}
.section-card {
  background-color: #d4af37; /* ذهبي */
  color: #fff;
  margin: 10px;
  padding: 15px;
  border-radius: 8px;
  min-width: 150px;
  text-align: center;
}
.section-card a {
  text-decoration: none;
  color: #fff;
}

/* تذييل الصفحة */
footer {
  background-color: #004d00; /* أخضر داكن */
  color: #fff;
  text-align: center;
  padding: 10px;
}
.social a {
  color: #d4af37;
  text-decoration: none;
  margin: 0 5px;
}
