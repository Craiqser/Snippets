# **[Snippets](../README.md) - Emmet**

[emmet.io](https://emmet.io/)

## HTML-шаблон

```bash
!
```

```html
<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta http-equiv="X-UA-Compatible" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
</head>
<body>

</body>
</html>
```

## Элемент с контентом

```bash
p{Содержимое}
```

```html
<p>Содержимое</p>
```

## Вложенные элементы

```bash
ul>li
```

```html
<ul>
	<li></li>
</ul>
```

Повторение с помощью знака *

```bash
ul>li*3>a
```

```html
<ul>
	<li><a href=""></a></li>
	<li><a href=""></a></li>
	<li><a href=""></a></li>
</ul>
```

Нумерация с помощью знака $

```bash
ul>li{$}*3
```

```html
<ul>
	<li>1</li>
	<li>2</li>
	<li>3</li>
</ul>
```

Вы можете использовать @ несколько раз, чтобы дополнить число ведущими нулями.
Можно установить базовое число с помощью "@N", а направление - с помощью "@-".

```bash
ul>li{$@-}*5
```

```html
<ul>
	<li>5</li>
	<li>4</li>
	<li>3</li>
	<li>2</li>
	<li>1</li>
</ul>
```

```bash
ul>li{$@10}*5
```

```html
<ul>
	<li>10</li>
	<li>11</li>
	<li>12</li>
	<li>13</li>
	<li>14</li>
</ul>
```

```bash
ul>li{$@-10}*5
```

```html
<ul>
	<li>14</li>
	<li>13</li>
	<li>12</li>
	<li>11</li>
	<li>10</li>
</ul>
```

## Классы и идентификаторы

Id указываются с помощью "#", а классы - с помощью ".".

```bash
div#main.container.responsive
```

```html
<div id="main" class="container responsive"></div>
```

## Пользовательские атрибуты

```bash
div[data-name=logo]
```

```html
<div data-name="logo"></div>
```

## Соседние элементы

```bash
header+div+footer
```

```html
<header></header>
<div></div>
<footer></footer>
```

## Группировка

```bash
div>(a>p>span+span)*3
```

```html
<div>
	<a href="">
		<p><span></span><span></span></p>
	</a>
	<a href="">
		<p><span></span><span></span></p>
	</a>
	<a href="">
		<p><span></span><span></span></p>
	</a>
</div>
```

## Элементы с типом

```bash
input:text
```

```html
<input type="text" name="" id="">
```

## Lorem Ipsum

```bash
lorem
```

```html
Lorem ipsum, dolor sit amet consectetur adipisicing elit. Assumenda, porro sed. Culpa odio delectus, accusantium excepturi velit soluta sunt, ad distinctio quasi facilis laborum molestiae deserunt ducimus perspiciatis, est minima?
```

```bash
lorem*3
```

```html
Lorem ipsum dolor sit amet consectetur adipisicing elit. Corrupti officia veritatis odio tenetur, similique esse commodi dolorem, possimus voluptatem id, iure nostrum. Maiores harum tempora explicabo quod ipsa ipsam rem.
Sunt aliquam neque eos doloremque corporis non et natus iste blanditiis dolore? Eum officiis voluptate optio doloribus dolores praesentium quod non iusto eos, saepe eveniet tenetur similique consequuntur corrupti facilis.
Ipsum exercitationem minima omnis quasi ratione dolores veniam ab excepturi optio laudantium vero ad sed debitis, impedit iusto. Illum sequi soluta saepe dolorum suscipit dolores ipsa nobis ipsum labore? Facere?
```

## CSS

```bash
m10-12-8-10
```

```css
margin: 10px 12px 8px 10px;
```

```bash
p10-12-8-10
```

```css
padding: 10px 12px 8px 10px;
```
