---
categories: [it, web]
tags: [Wordpress]
demo: http://demo.arconixpc.com/arconix-shortcodes/
link: https://wordpress.org/plugins/arconix-shortcodes/
update: 2018
---

# Обзор плагина Arconix Shortcodes для WordPress

Малопопулярный плагин с шорткодами был выбран мной из ряда других в первую очередь простотой и красивыми по умолчанию элементами без ядовитых цветов, градиентов и так далее. Умеет делать кнопки, текстовые блоки, и другие красивые вещи.

**Update 2018.** Пользовался этим плагином, когда держал собственный сайт на Wordpress.

## Установка

Страница плагина на <https://wordpress.org/plugins/arconix-shortcodes/>.

Устанавливается, как и все остальные плагины. В режиме редактирования статьи справа внизу появляется следующая панель:

![Панель Arconix Shortcodes в WordPress](img/arconix-shortcode-list.png)

Как я понял, она носит лишь информативный характер. Ну что ж, пусть плагин и не удобен в использовании, зато результат его удобен. К тому же я лично многие из них повесил на плагин [AddQuicktag](https://wordpress.org/plugins/addquicktag/).

## Текстовые блоки

Ради них и взял фактически этот плагин:

```html
[box]Простой блок[/box]
```

![Простой блок](img/box.png)

```html
[box color="blue"]Блок с синей заливкой[/box]
```

![Блок с синей заливкой](img/box-blue.png)

```html
[box color="green"]Блок с зеленой заливкой[/box]
```

![Блок с зеленой заливкой](img/box-green.png)

```html
[box color="grey"]Блок с серой заливкой[/box]
```

![Блок с серой заливкой](img/box-grey.png)

```html
[box color="red"]Блок с красной заливкой[/box]
```

![Блок с красной заливкой](img/box-red.png)

```html
[box color="tan"]Блок с дубильной заливкой[/box]
```

![Блок с дубильной заливкой](img/box-tan.png)

```html
[box color="yellow"]Блок с желтой заливкой[/box]
```

![Блок с желтой заливкой](img/box-yellow.png)

```html
[box color="orange"]Блок с оранжевой заливкой[/box]
```

![Блок с оранжевой заливкой](img/box-orange.png)

```html
[box style="alert"]Блок с предупреждением[/box]
```

![Блок с предупреждением](img/box-alert.png)

```html
[box style="comment"]Блок с комментарием[/box]
```

![Блок с комментарием](img/box-comment.png)

```html
[box style="download"]Блок с загрузкой[/box]
```

![Блок с загрузкой](img/box-download.png)

```html
[box style="info"]Блок с информацией[/box]
```

![Блок с информацией](img/box-info.png)

```html
[box style="tip"]Блок с советом[/box]
```

![Блок с советом](img/box-tip.png)

```html
[box icon="fa-bolt" color="orange"]Блок с оранжевой заливкой и иконкой[/box]
```

![Блок с оранжевой заливкой и иконкой](img/box-orange-bolt.png)

Обратите внимание, что вы можете указать свою иконку в виде названия любой иконки из шрифта [Font-Awesome](https://fontawesome.com/icons).

## Спойлеры

Вот это полезная штука. Мне нравится:

```html
[toggle title="Спойлер"]Текст спойлера[/toggle]
```

[Спойлер](img/toggle_01.mp4)

Или вот так нагляднее:

[Спойлер](img/toggle_02.mp4)

## Кнопки

Кнопки, при нажатии на которые, производится переход на какую-то страницу.

Простая кнопка:

```html
[button url="http://blog.harrix.org" style="flat"]Кнопка[/button]
```

![Простая кнопка](img/button.png)

Кнопка может быть нескольких цветов (`color = black, blue, green, grey, orange, pink, red, white`):

```html
[button url="http://blog.harrix.org" color="black" style="flat"]Кнопка[/button]
```

![Кнопка черная](img/button-black.png)

```html
[button url="http://blog.harrix.org" color="blue" style="flat"]Кнопка[/button]
```

![Кнопка синяя](img/button-blue.png)

```html
[button url="http://blog.harrix.org" color="green" style="flat"]Кнопка[/button]
```

![Кнопка зеленая](img/button-green.png)

```html
[button url="http://blog.harrix.org" color="grey" style="flat"]Кнопка[/button]
```

![Кнопка серая](img/button-grey.png)

```html
[button url="http://blog.harrix.org" color="orange" style="flat"]Кнопка[/button]
```

![Кнопка оранжевая](img/button-orange.png)

```html
[button url="http://blog.harrix.org" color="red" style="flat"]Кнопка[/button]
```

![Кнопка красная](img/button-red.png)

```html
[button url="http://blog.harrix.org" color="white" style="flat"]Кнопка[/button]
```

![Кнопка белая](img/button-white.png)

Кнопки могут быть трех размеров (`size = small, medium, large`):

```html
[button url="http://blog.harrix.org" size="small" style="flat"]Кнопка[/button]
```

![Кнопка маленькая](img/button-small.png)

```html
[button url="http://blog.harrix.org" size="medium" style="flat"]Кнопка[/button]
```

![Кнопка средняя](img/button-medium.png)

```html
[button url="http://blog.harrix.org" size="large" style="flat"]Кнопка[/button]
```

![Кнопка большая](img/button-large.png)

Кнопки могут быть трех стилей (`style = classic, flat, clear`):

```html
[button url="http://blog.harrix.org" style="classic"]Кнопка[/button]
```

![Кнопка классическая](img/button-classic.png)

```html
[button url="http://blog.harrix.org" style="flat"]Кнопка[/button]
```

![Кнопка плоская](img/button-flat.png)

```html
[button url="http://blog.harrix.org" style="clear"]Кнопка[/button]
```

![Кнопка контурная](img/button-clear.png)

Страница может открываться либо в той же вкладке или в новой (`target = self, blank`).

В той же:

```html
[button url="http://blog.harrix.org" target="self" style="flat"]Кнопка[/button]
```

В другой вкладке:

```html
[button url="http://blog.harrix.org" target="blank" style="flat"]Кнопка[/button]
```

Все параметры могут сочетаться:

```html
[button url="http://blog.harrix.org" color="orange" size="large"]Кнопка[/button]
```

![Кнопка классическая, оранжевая и большая](img/button-orange-classic-large.png)

```html
[button url="http://blog.harrix.org" color="black" size="small" target="blank"]Кнопка[/button]
```

![Кнопка классическая, черная и маленькая](img/button-black-classic-small.png)

## Вкладки

```html
[tabs] [tab title="Вкладка 1"] Первый блок информации [/tab] [tab title="Вкладка 2"] Второй блок информации [/tab] [tab
title="Вкладка 3"] Третий блок информации [/tab] [/tabs]
```

![Вкладки](img/tabs.png)

## Разное

### Пояснение при наведении на слово — всплывающая подсказка (В общем объяснение чего-то)

```html
[abbr title="По моему скромному мнению"]ИМХО[/abbr]
```

[Всплывающая подсказка](img/abbr.mp4)

### Выделенный текст

```html
[highlight]текст[/highlight]
```

![Выделенный текст](img/highlight.png)

### Ссылка на ваш сайт

```html
[site-link]
```

[Ссылка на ваш сайт](img/site-link.mp4)

### Данные о текущем годе

```html
[the-year before="©" start="2001" after="All Rights Reserved"]
```

![Данные о текущем годе](img/the-year.png)

### Ссылка на сайт Wordpress

```html
[wp-link]
```

[Ссылка на сайт Wordpress](img/wp-link.mp4)

Более подробную исходную документацию можете прочитать тут: <https://www.tychesoftwares.com/docs/docs/shortcodes/>.
