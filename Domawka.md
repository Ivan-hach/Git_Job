# Команды для работы в терминале Git облегчающие жизнь.

_Git — это развитая система контроля версий с активной поддержкой и открытым исходным кодом, которую используют тысячи разработчиков из разных точек мира._

*** 

##### Команда для инициализации текущей директории.

```sh
git init
```

***

##### Команда добавляет файл в текущий индекс.

```sh
git add
```

***

##### Команда показывает состояния файлов в рабочей директории и индексе: какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе. Вдобавок к этому выводятся подсказки о том, как изменить состояние файлов.

```sh
status
``` 

***

##### Команда фиксирует изминения (до выполнения этой команды локальные изминения ни куда не запишутся)

```sh
commit -m"комментарий к текущей директории"
```

***

##### Команда используется для просмотра истории коммитов, начиная с самого свежего и уходя к истокам проекта. По умолчанию, она показывает лишь историю текущей ветки, но может быть настроена на вывод истории других, даже нескольких сразу, веток. Также её можно использовать для просмотра различий между ветками на уровне коммитов.

```sh
git log
```

***

##### Команда для сокращённого просмотра commit -m

```sh
git log --onelin
```

***

##### Команда используется для переключения веток и выгрузки их содержимого в рабочую директорию.

```sh
git checkout
```

***

##### Команда показывает текущую версию GIT
```
git version
```

***

##### Команда показывает изминения и отличия между любыми GIT деревьями.
```sh
git diff
```

***

##### Команда для удаления файлов из индекса рабочей директории.

```sh
git rm 
```
***
### Команды для работы с ветками.

***

##### Команда выводит список веток, где мы можем посмотреть на какой ветке мы сейчас находимся.

```sh
git branch
```

###### | _Для того что бы создать новую ветку мы к команде git branch пишем любой текс(название)без пробелов.В место пробела ставим нижнее подчёркивание_ ( _ )

```sh
Например:
git branch new_txt
```

***

##### Команда помогает переключаться по веткам.

```sh
git checkout <имя ветки>
```

***

##### Команда которая удаляет всю историю из терминала.

```sh
clear
```
***

##### Команда выполняет слияние отдельных направлений разработки, созданных с помощью команды git branch , в единую ветку.

```sh
git merge
```
**Важно:** 
Перед тем как написать комманду о слиянии созданной ветки с веткой *__Master__*, нужно убедиться что мы на ветке мастер а не на какой другой!

_Например вот так:_

```sh 
git merge <name_branch>
```

***

##### Команда для удаления ненужных веток, в которых мы уже отработали.

```sh
git branch -d <Имя_ветки>
```
***
##### Команда визуально показывает наш путь слияния веток.

```sh
git log --graph
    или
got log --oneline --graph    
```
##### Команда используется для извлечения и загрузки содержимого из удаленного репозитория и немедленного обновления локального репозитория этим содержимым.
```sh
git pull
```

##### Команда позволяет отправлять локальную ветку на удаленный репозиторий.
```sh
git push
```

# Синтаксис языка _MarkDaun_

## __запомнить:__
* Жирный текст - __**__ (Ставится в начале и в конце того текста который надо выделить)

* Курсивный текст - __*__ (Ставится в начале и в конце того текста который надо выделить)

    **1**. Так же __*__ можно заменить нижним подчёркиванием **_**

* Зачёркнутый текс - **~** (Тильда)

* Выделяют заголовки - **#** в начале строки

* Показать уровень заголовка - подчёркивание знаками **= или-**

* Нумерованные списки обозначаются обычными __цифрами 1,2,3__

* Ненумерованные списки - обозначаются **знаками * в начале строки**

* Вложенные списки - выполняем отступ 

На сайте [Doka](https://doka.guide/tools/markdown/) есть ещё много интересных фишечек.

***


##### Звёздочки рисуют разделительные линии, ставить можно от 3 до 6
```sh
***
```
# Полезныё ссылки для работы с Git

***

__список сайтов:__

1.  [Хабр](https://habr.com/ru/companies/ruvds/articles/599929/)

2. [ilfire.ru](https://ilfire.ru/kompyutery/shpargalka-po-sintaksisu-markdown-markdaun-so-vsemi-samymi-populyarnymi-tegami/?upm_export=print)

3. [proglib](https://proglib.io/p/git-cheatsheet)

4. [htmlacasemy.ru](https://habr.com/ru/companies/ruvds/articles/599929/)

5. [Doka](https://doka.guide/tools/markdown/) 

***
# Так же в MarkDoun можно вставлять картинки.

### Например вот так:
```sh
![Имя](Ссылка на кртинку)
```

![Cat](Cat.jpg)

## Логотип _MarkDown_
***
![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/1280px-Markdown-mark.svg.png)

***

Белое море у берегов которого мы живём и строим атомный подводный флот.На берегах моего дома о.Ягры есть заповедник, и таких мест во всём мире только два, в Северодвинске и Калининграде.
![White Sea](Sea.jpg)

***
# Цитаты великих людей в программировании.

> Я всегда мечтал о том, чтобы моим компьютером можно было пользоваться так  же легко, как телефоном; моя мечта  сбылась: я уже не могу разобраться, как пользоваться моим телефоном.
>
> *-Bjarne Stroustrup*

> Обучение программированию не может научить быть экспертом, так же как и изучение кистей и красок не может превратить кого либо в художника.
>
>*-Eric S.Raymond*

>Вы не можете создавать хорошие программы без хорошей команды, но большинство софтверных команд ведут себя как проблемная семья.
>
>*-Jim McCarthy*


## Заключение:

***
_Язык_ __MarkDaun__ _очень интересный,одно удовольствие пробовать что то писать и менять текс прибегая к простым символам. Выше указанная информация по удобству использования языка_ __MarkDaun__ _это малая часть которую я попробовал описать в своей первой домашней работе.Что бы узнать больше функционала советую посетить выше указанные сайты, там ты найдешь много интересного и полезного :)_ 




