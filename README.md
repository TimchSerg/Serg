# testing_learn_git - репозиторий созданный для просмотра функций(возможностей) git
  
## Параллельно с этим, будет использоваться язык разметки как [Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637#Links "Инструкция по использованию Markdown")

  

    

### Так же используется **git flow**

Начнем
=======

## pull-request
 > Pull request'ы позволяют вам рассказать другим о тех изменениях, которые вы разместили в своём GitHub-репозитории. 
 > [Источник](https://habr.com/ru/post/125999/)

> удалить ветку, в которой велась разработка:  
> git branch -d feature #В локальном репозитории  
> git push origin :feature #В удалённом репозитории   
  

Для того что бы залить изменения и сделать pull request необходимо:
1. Перейти на страницу нашего репозитория на GitHub, и нажимаем кнопку Pull Requests.
2. Выбираем необходимую нам ветку и ветку в какую мы делаем изменения
2. Далее, нажимаем кнопку Create Pull Requests.
3. Мы поподаем на страницу описания нашего pull request. Вводим комментарий и нажимаем кнопку Create pull request
4. После того как наши изменения приняли и pull request закрыт. __Не забываем делать git pull__

## Как писать примечания к релизу?

Содержание документа зависит от типа релиза. Вот пример основных пунктов:

- Заголовок с названием продукта, датой релиза и его номером, версией примечания.
- Краткая информация — обзор продукта и изменений.
- Ссылки на инструкции по установке, руководство для пользователя, архив, если необходимо.
- Цели — краткий обзор целей примечаний к релизу с перечислением нового в этой версии (исправления ошибок и новые функции).
- Резюме — краткое описание ошибок и проблем.
- Шаги по устранению ошибок.
- Решение — оптимизация, которая была сделана для исправления ошибок.
- Влияние пользователей и поддержки, если необходимо.
- Примечания — все примечания относительно установки продукта, его обновлений и документации.
- Юридическая информация — лицензии, гарантии, отказ от ответственности и т.д.
- Контакты — контактная информация службы поддержки продукта.

[Источник](https://habr.com/ru/company/hygger/blog/358204/)