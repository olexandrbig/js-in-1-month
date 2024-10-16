# 6-css

## Introduction

Мова CSS дозволяє видозмінювати HTML елементи і генерувати навіть віртуальні блоки або елементи 

Є 3 ключових способи писати стилі у форматі CSS:

1. Прямо в HTML розмітці як атрибут тегу, тоід стилі впливають саме на тег і його вміст `<h1 style="background-color:DodgerBlue;">Hello World</h1>`
2. З використанням html елементу style тоді потрібно додати стилі за атрибутом або селектором `<style>h1{background-color:DodgerBlue;}</style>`
3. Зовнішній файл `<link href="main.css" rel="stylesheet">` всередині якого будуть стилі у форматі `h1{background-color:DodgerBlue;}`

В рамках цього уроку ми будемо детально розглядати саме перший варіант

## CheetSheet

[Кольори](https://www.w3schools.com/css/css_colors.asp)

[Фони](https://www.w3schools.com/css/css_background.asp)

[Рамки](https://www.w3schools.com/css/css_border.asp)

[Відступи](https://www.w3schools.com/css/css_margin.asp)

[Розтягнення](https://www.w3schools.com/css/css_padding.asp)

[Обведення](https://www.w3schools.com/css/css_outline.asp)

[Робота з текстом](https://www.w3schools.com/css/css_text.asp)

Це далеко не повний список але саме з нього ми почнемо

## Завдання
Стилізувати сторінку використовуючи різні значення в атрибуті style відповідно до першого способу

`<h1 style="background-color:DodgerBlue;">Hello World</h1>`
