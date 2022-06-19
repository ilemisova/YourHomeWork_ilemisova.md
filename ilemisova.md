# Инструкция по работе с git

* *git --version* команда отображения текущей версии
* *git --status* команда отображающая текущий статус
* *git --init* команда инициализации репозитория
* *git --add* команда для обозначения актуальных состояний
* *git --commit* команда для фиксации изменений
* *git --log* команда для отображения всех commits

## Базовые команды со второго семинара

* *git branch* - команда, отображающая в терминале список существующих веток
* *git branch branch_name* - команда, создающая ветку с именем *branch_name* 

## Базовые команды с третьей лекции
* *git branch -d* -команда для удаления ветки

* *git clone* - команда для клонирования внешнего репозитория на свой ПК

* *git pull* - команда позволяет скачать все из текущего репозитория и сделать авто merge
* *git push* - позволяет отправить свою версию репозитория на внешний репозиторий
* *git diff* - показывает разницу между текущим файлом и сохраненным

### Синтаксис языка Markdown

* Жирный текст -* - чтобы текст выделить жирным необходимо поставить дефис и звездочку

* *Курсивный текст* - чтобы текст выделить курсивом необходимо выделить начало и конец звездочками

* # Выделение заголовков - чтобы выделить залоговок, необходимо поставить знак решетки

*  Вложенные списки - необходимо выполнить отступы

#### Инструкция по работе с удаленным репозиторием

* *git clone* - копирование внешнего репозитория на ПК
* *git push* - отправка моей версии репозитория  на внешний репозиторий
* *git pull* - скачивание всей информации на локальный репозиторий + автоматический merge с моей версией

Важно авторизовать Visual Code и Git Hub (авторизация на внешнем репозитории)

##### Как сделать Pull request:

* Делаем fork репозитория
* Делаем clone СВОЕЙ версии репозитория
* Создаем новую ветку и в НЕЕ вносим свои изменения
* Фиксируем изменения (делаем коммиты)
* Отправляем свою версию в свой GitHub
* На сайте GitHub нажимаем кнопку pull request