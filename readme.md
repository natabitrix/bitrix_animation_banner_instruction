<h2>Инструкция по баннерам</h2>

<ol>
    <li>изменить путь к внешнему файлу скрипта</li>
    <li>во внешнем файле скрипта изменить путь к картинкам (library properties)</li>
    <li>в коде баннера создать функцию с уникальным названием, напр. init_banner_name()</li>
    <li>в созданной функции init_banner_name() прописать вызов скриптов баннера, а также вызов функции init();</li>
    <li>добавить созданную функцию в массив _init, например _init.push(init_banner_name);</li>
    <li>в html-коде баннера удалить стили и параметры блоков (они не используются)</li>
    <li>переименовать все id блоков в html-коде баннера на уникальные, например animation_container_banner_name</li>
    <li>в скрипте баннера в функции init(), в document.getElementById("...") изменить id на прописанные в html-коде</li>
</ol>

<hr>

<h3>Пример</h3>
<a href="https://github.com/natabitrix/bitrix_animation_banner_instruction/blob/master/banner_code_before.txt" target="_blank">⇒ Пример кода "до"</a><br>
<a href="https://github.com/natabitrix/bitrix_animation_banner_instruction/blob/master/banner_code_after.txt" target="_blank">⇒ Пример кода "после"</a>

<br>
<a href="https://github.com/natabitrix/bitrix_animation_banner_instruction/commit/9b090ab77ff293bef007e7dd847f330384702669?diff=split" target="_blank">⇒ Сравнение изменения кода (слева "до", справа "после")</a>

<br>
<br>
