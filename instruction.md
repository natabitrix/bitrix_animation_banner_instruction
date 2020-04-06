<h2>Инструкция по баннерам</h2>

<ol>
    <li>переписать пути к скриптам</li>
    <li>создать функцию с уникальным названием, напр. init_banner_name()</li>
    <li>в созданной функции init_banner_name() прописать вызов скриптов баннера, а также вызов функции init();</li>
    <li>добавить созданную функцию в массив _init, например _init.push(init_banner_name);</li>
    <li>переименовать все id блоков в html-коде баннера на уникальные, например animation_container_banner_name</li>
    <li>в скрипте баннера в функции init() изменить id на прописанные в хтмл-коде</li>
    <li>в файле скрипта баннера изменить путь к картинкам (library properties)</li>
</ol>

<hr>

<h3>Пример</h3>
<a href="https://github.com/natabitrix/ustinka_banner_instruction/blob/master/banner_code_before.txt" target="_blank">⇒ Пример кода "до"</a><br>
<a href="https://github.com/natabitrix/ustinka_banner_instruction/blob/master/banner_code_after.txt" target="_blank">⇒ Пример кода "после"</a>

<br>
<a href="https://github.com/natabitrix/ustinka_banner_instruction/commit/9b090ab77ff293bef007e7dd847f330384702669?diff=split" target="_blank">⇒ Сравнение изменения кода (слева "до", справа "после")</a>

<br>
<br>

