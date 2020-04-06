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

[Пример кода "до"](https://github.com/natabitrix/ustinka_banner_instruction/blob/master/banner_code_before.txt)<br>
[Пример кода "после"](https://github.com/natabitrix/ustinka_banner_instruction/blob/master/banner_code_after.txt)<br>

<br>
[Сравнение изменения кода (слева "до", справа "после")]
(https://github.com/natabitrix/ustinka_banner_instruction/commit/9b090ab77ff293bef007e7dd847f330384702669?diff=split)
