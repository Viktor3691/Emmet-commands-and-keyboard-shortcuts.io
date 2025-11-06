<!-- DOCTOC SKIP -->

# Emmet-commands-and-Keyboard-Shortcuts.io

<img src="IMG/53.png" alt="53" class="pictures1">

<h2 id="Content1"><img src="./IMG/icon.png" alt="icon" width="20"> Содержание</h2>

<ol>
<li><a href="#Content2" class="underline">Расширение аббревиатур</a>

<ol>
    <li><a href="#Content21" class="underline">Синтаксис сокращений</a></li>
    <li><a href="#Content22" class="underline">Операторы вложенности</a></li>
    <li><a href="#Content23" class="underline">Умножение</a></li>
    <li><a href="#Content24" class="underline">Комбинирование</a></li>
    <li><a href="#Content25" class="underline">Операторы атрибутов</a></li>
    <li><a href="#Content26" class="underline">Добавляем текст</a></li>
    <li><a href="#Content27" class="underline">«Рыба» текста — Lorem Ipsum</a></li>
    <li><a href="#Content28" class="underline">Псевдонимы</a></li>

</ol>

</li>

<li><a href="#Content3" class="underline">Emmet actions (<i>Действия Эммета</i></a> )
<ol>
    <li><a href="#Content31" class="underline">Как настроить параметры Emmet?</a></li>
    <li><a href="#Content32" class="underline">Меню привязки ключей Emmet</a></li>
    <li><a href="#Content33" class="underline">Итог настройки Emmet</a></li>
    <li><a href="#Content34" class="underline">Удалить Тег</a></li>
    <li><a href="#Content35" class="underline">Баланс (Входящий)</a></li>
    <li><a href="#Content36" class="underline">Баланс (Исходящий)</a></li>
    <li><a href="#Content37" class="underline">Вычислить Математическое выражение</a></li>
    <li><a href="#Content38" class="underline">Перейдите к Соответствующей паре</a></li>
    <li><a href="#Content39" class="underline">Перейти к следующей точке изменения</a></li>
    <li><a href="#Content310" class="underline">Перейти к предыдущей точке изменения</a></li>
    <li><a href="#Content311" class="underline">Объединить строки</a></li>
    <li><a href="#Content312" class="underline">Отразить CSS-значение</a></li>
    <li><a href="#Content313" class="underline">Выбрать следующий элемент</a></li>
    <li><a href="#Content314" class="underline">Разделить/объединить тег</a></li>
    <li><a href="#Content315" class="underline">Переключить комментарий</a></li>
    <li><a href="#Content316" class="underline">Обновить размер изображения</a></li>
    <li><a href="#Content317" class="underline">Обновить тег</a></li>
    <li><a href="#Content318" class="underline">Перенести с сокращением</a></li>
    <li><a href="#Content319" class="underline">Уменьшить на 0,1</a></li>
    <li><a href="#Content320" class="underline">Уменьшить На 1</a></li>
    <li><a href="#Content321" class="underline">Уменьшить На 10</a></li>
    <li><a href="#Content322" class="underline">Увеличить на 0,1</a></li>
    <li><a href="#Content323" class="underline">Увеличить на </a>1</li>
    <li><a href="#Content324" class="underline">Увеличить на 10</a></li>

</ol>
</li>
</ol>

<p><a href="https://docs.emmet.io/" target="_blank" rel="noopener noreferrer">
Документация Emmet.</a>
    </p>

<div class="container_text">
<h2 id="Content2"><a class="anchor" href="#Content2">#</a>Расширение аббревиатур </h2>

<p>Сокращения - это основа инструментария Emmet: эти специальные выражения анализируются во
    время выполнения и
    преобразуются в структурированный блок кода, например, HTML. <br>Синтаксис аббревиатур
    похож
    на CSS-селекторы с несколькими
    расширениями, специфичными для генерации кода. Так что каждый веб-разработчик уже знает,
    как им пользоваться.

    Вот пример: эта аббревиатура</p>

<strong>#page&gt;div.logo+ul#navigation&gt;li\*5&gt;a{Item $}</strong>

<div class="ramka">
    &lt;div id="page"&gt; <br>
    &nbsp;&nbsp;&lt;div class="logo"&gt;&lt;/div&gt; <br>
    &nbsp;&nbsp;&lt;ul id="navigation"&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;&lt;a href=""&gt;Item 1&lt;/a&gt;&lt;/li&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;&lt;a href=""&gt;Item 2&lt;/a&gt;&lt;/li&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;&lt;a href=""&gt;Item 3&lt;/a&gt;&lt;/li&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;&lt;a href=""&gt;Item 4&lt;/a&gt;&lt;/li&gt;<br>
    &nbsp;&nbsp;&nbsp;&nbsp;&lt;li&gt;&lt;a href=""&gt;Item 5&lt;/a&gt;&lt;/li&gt;<br>
    &nbsp;&nbsp;&lt;/ul&gt;<br>
    &lt;/div&gt;
</div>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

**Table of Contents** _generated with [DocToc](https://github.com/thlorenz/doctoc)_

- [Emmet-commands-and-Keyboard-Shortcuts.io](#emmet-commands-and-keyboard-shortcutsio)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->
