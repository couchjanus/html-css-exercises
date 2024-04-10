# html-css-exercises

HTML/CSS practice exercises

## Exercises for lecture #5 Одиниці виміру в CSS. Шрифти

- Відвідайте веб-сайт Google Fonts (https://fonts.google.com/).
- Знайдіть шрифти, який ви хочете використовувати. Потрібно вибрати 3 сімейства шрифтів - serif, sans-serif і monospace.
- Виберіть потрібні стилі та щільність для кожного з шрифтів.
- Додайте вибрані шрифти за допомогою правила @import у файл CSS css/app.css

- Визначити у файлі CSS css/app.css селектор body. Встановити для нього такі властивості:

    - сімейство шрифтів - підключений Google Fonts сімейства sans-serif
    - розмір шрифту - 1rem 
    - вагу шрифту - 400
    - висоту рядка - 1.5
    - колір - #212529
 
- Підключити бібліотеку векторних іконок (http://fontawesome.io/) до сторінки  
- Вибрати з бібліотеки fontawesome векторні іконки, що символізують соціальні мережі facebook, twitter, youtube, google.

- У розділі підвал створити колонку для посилань на соціальні мережі. Замінити слова facebook, twitter, youtube, google на відповідні іконки.

```html
<div class="col">
    <ul class="list-inline">
        <li class="list-inline-item"><a class="social-icon" href="#">facebook</a></li>
        <li class="list-inline-item"><a class="social-icon" href="#">twitter</a></li>
        <li class="list-inline-item"><a class="social-icon" href="#">youtube</a></li>
        <li class="list-inline-item"><a class="social-icon" href="#">google</a></li>
    </ul>
</div>
```

- Вибрати з бібліотеки fontawesome векторні іконки, що символізують кошик замовлення, список бажань, реєстрація на сайті.

- У розділі навігація, який містить список ul з класом navbar-nav, що знаходиться справа, замінити написи 'кошик замовлення', 'список бажань', 'реєстрація на сайті' на відповідні іконки.

```html
<ul class="navbar-nav">
    <li class="nav-item">
        <a class="nav-link text-uppercase" href="cart.html">
            кошик замовлення
        </a>
    </li>
    <li class="nav-item me-3">
        <a class="nav-link text-uppercase" href="#">
            список бажань
        </a>
    </li>
    <li class="nav-item">
        <a class="nav-link text-uppercase" href="login.html">
            реєстрація на сайті
        </a>
    </li>
</ul>
```
