# Django_Intro
 
В течение данного модуля вы должны были выполнить следующие задания:

Создать проект Django.
Добавить в него 3 статические странички.
На одной из страниц контент повторяется 2 раза без изменения content (два раза прописано {{ flatpage.content }}).
Одна из страниц на сайте доступна только админу (только вошедшему пользователю).
На одной из страниц изменены шрифты и размеры текста.
Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными.
Статические файлы Bootstrap загружаются через теги {% load static %} и {% static %}.


В данном репозитории вы можете видеть:

1) Созданный проект Django_project
2) В котором помимо 2 созданных страничек внутри курса было создано еще 3 странички:
        <hr> * - Documents (контент повторяется 2 раза без изменения content)
        <hr> * - Info (изменены шрифты и размеры текста)
        <hr> * - Haters (Одна из страниц на сайте доступна только админу (только вошедшему пользователю))
3) Сайт представляет собой оформленный Bootstrap-шаблон со встроенными пользовательскими данными.
4) Статические файлы Bootstrap загружаются через теги {% load static %} и {% static %}.

Пы.Сы. Размер текста и отступы для красоты от себя добавил на все страницы)
      + исправил шаблоны новых страниц с использованием тега {% extends ….. %} чтобы наследовать шапку, а не терять ее.     
