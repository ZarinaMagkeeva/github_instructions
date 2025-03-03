﻿# github_instruction
# Инструкция по работе с GitHub
-------------------------------------
![](images/gitHead.jpeg)

- [Инструкция по GitHub](#инструкция-по-github)
  - [Что такое GitHub и чем он отличается от Git](#что-такое-github-и-чем-он-отличается-от-git)
  - [Регистрация и установка](#регистрация-и-установка)
  - [Репозиторий и работа с ним](#репозиторий-и-работа-с-ним)
    - [Что такое репозиторий](#что-такое-репозиторий)
    - [Cоздание репозитория](#cоздание-репозитория)
    - [Изменения в репозитории](#изменения-в-репозитории)
    - [Просмотр файлов в репозитории](#просмотр-файлов-в-репозитории)
  - [Зафиксируйте свое первое изменение](#зафиксируйте-свое-первое-изменение)
  - [Как работать с чужим репозиторием, присоединится к проекту. Pull request.](#как-работать-с-чужим-репозиторием-присоединится-к-проекту-pull-request)
  - [Работа с удаленными репозиториями локально](#работа-с-удаленными-репозиториями-локально)
    - [Просмотр удалённых репозиториев](#просмотр-удалённых-репозиториев)
    - [Настройка удалённых репозиториев](#настройка-удалённых-репозиториев)
  - [Что же такое Codespaces?](#что-же-такое-codespaces)
      - [Для кого это?](#для-кого-это)
    - [Как попасть в Codespaces?](#как-попасть-в-codespaces)
  - [Про devcontainers](#про-devcontainers)
    - [Вливание/предложение изменений в сторонний репозиторий](#вливаниепредложение-изменений-в-сторонний-репозиторий)
  - [Что такое SSH? ](#что-такое-ssh-)

## Что такое GitHub и чем он отличается от Git
![](images/0.Git_and_GitHub.PNG)

**Git** — это система контроля версиями. [GitHub](https://github.com/) это облачная платформа для хранения кода. Здесь можно попрактиковаться в разработке и придумать что-то свое, найти множество open-source проектов, передовых технологий, различных функций и дизайнов. А еще вы можете создавать сайты бесплатно напрямую из репозитория!

GitHub пользуются все: это один из важных общих навыков вне зависимости от выбранного вами языка программирования и направления разработки. И, как и школьные уроки ОБЖ, тот же git clone когда-нибудь вас спасёт.
Поэтому важно начинать пользоваться GitHub как можно раньше — хотя бы даже для бэкапов учебного кода, и уже скоро это станет полезной привычкой.

## Регистрация и установка

Зайдите на GitHub и создайте свой аккаунт. В принципе, этим можно и ограничиться. При желании можете установить Git. Но для работы с GitHub это вовсе не обязательно. Однако если вы планируете заниматься проектами на локальном компьютере, то установка вам все-таки нужна.

## **Репозиторий и работа с ним**

### Что такое репозиторий

**Репозиторий** — это место, в котором вы систематизируете свой проект. Здесь вы храните файлы, папки, видео, изображения, блокноты Jupyter Notebook, наборы данных и т.д.

Загрузить в репозиторий можно всё что угодно, но предполагается, что вы будете хранить в нём файлы с исходным кодом и какие-нибудь дополнительные материалы.

Репозитории могут быть публичными и приватными, в них можно создавать другие папки и отслеживать изменения версий.

Перед началом работы с Git необходимо *инициализировать* репозиторий для проекта и правильно его подготовить. Это можно сделать на сайте GitHub.

Лучше сразу добавлять в репозиторий _**README-файл**_ с информацией о проекте. Это можно сделать в момент создания репозитория, поставив галочку в соответствующем поле.

### Cоздание репозитория

В репозиториях GitHub можно хранить различные проекты, в том числе проекты с открытым исходным кодом. Проекты с открытым исходным кодом позволяют обмениваться кодом для создания более качественного и надежного программного обеспечения. Репозитории можно использовать для совместной работы с другими пользователями и отслеживания своей работы. 

1. В правом верхнем углу любой страницы воспользуйтесь выпадающим меню + и выберите пункт Новое хранилище.

<img src = "https://docs.github.com/assets/cb-31554/mw-1440/images/help/repository/repo-create.webp" width ="200px">


2. Введите короткое, запоминающееся имя вашего репозитория. Например, "hello-world".

<img src = "https://docs.github.com/assets/cb-61138/mw-1440/images/help/repository/create-repository-name.webp" width ="450px">

3. По желанию добавьте описание вашего репозитория. Например, "Мой первый репозиторий на GitHub".

4. Выберите видимость репозитория. Будет ли он публичный или закрытый.

5. Инициализируйте этот репозиторий с помощью README, для того, чтобы просматривающие ваш репозиторий понимали, о чем тут идёт речь.

6. Нажмите кнопку Создать репозиторий.

**Поздравляем! Вы успешно создали свой первый репозиторий и инициализировали его файлом README.**

### Изменения в репозитории

Вносить изменения в проект можно двумя способами. Изменять файлы/блокноты на компьютере либо делать это на сайте GitHub.

Допустим, вам захотелось подкорректировать README-файл на сайте GitHub.

1. Для начала *перейдите* в ваш репозиторий.
2. Для выбора файла кликните по его названию (например, кликните по **README.md** для перехода к файлу-описанию).
3. В верхнем правом углу вы увидите иконку с карандашом. Нажмите на нее для внесения изменений.
4. Напишите короткое сообщение, передающее суть изменений (и подробное описание, если сочтете это нужным).
5. Нажмите кнопку Commit changes.

Но для обучения Тёмной стороне Силы работе с GitHub полезно потренироваться выполнять и другие необходимые в процессе разработки действия: клонирование/форк, объединение веток, просмотр и разрешение конфликтов и другие.

### Просмотр файлов в репозитории

![](images/repo5.png)

Согласитесь, что в ряде случаев удобно не скачивать исходники, а просто бегло ознакомиться с ними. Для таких простых операций вовсе не нужен десктопный клиент: все файлы можно быстро открыть в веб-версии (и код, и те же картинки). Просто щёлкните по ним для просмотра!



## Зафиксируйте свое первое изменение
Коммит - это как снимок всех файлов проекта в определенный момент времени.

Когда вы создавали новый репозиторий, вы инициализировали его файлом README. Файлы README - это отличное место для более подробного описания проекта или добавления документации, например, по установке или использованию проекта. Содержимое файла README автоматически отображается на первой странице репозитория.


** Давайте зафиксируем изменения в файле README. **

1. В списке файлов репозитория выберите README.md.

<img src = "https://docs.github.com/assets/cb-21025/mw-1440/images/help/repository/create-commit-open-readme.webp" width ="450px">

2. В правом верхнем углу окна просмотра файлов щелкните мышью, чтобы открыть редактор файлов.

<img src = "https://docs.github.com/assets/cb-47677/mw-1440/images/help/repository/edit-file-edit-button.webp" width ="450px">



3. В текстовом поле введите информацию о себе.

4. Над новым содержимым нажмите кнопку Preview (Просмотр).

<img src = "https://docs.github.com/assets/cb-35443/mw-1440/images/help/repository/edit-readme-preview-changes.webp" width ="450px">

5. Просмотрите изменения, внесенные в файл. Если выбрать опцию Show diff, то новое содержимое будет выделено зеленым цветом.

<img src = "https://docs.github.com/assets/cb-32483/mw-1440/images/help/repository/create-commit-review.webp" width ="450px">

6. Нажмите кнопку Зафиксировать изменения.

7. В поле "Сообщение о фиксации" введите короткое, содержательное сообщение о фиксации, описывающее изменения, внесенные в файл. В сообщении о фиксации можно приписать фиксацию более чем одному автору. 

## **Как работать с чужим репозиторием, присоединится к проекту. Pull request.**

*  Получить ссылку на чужой репозиторий (который собираемся клонировать)

* Залогиниться в свой github

* На новой вкладке браузера : копируем в адресную строку ссылку на чужой репозиторий

* В интерфейсе github нажимаем кнопку Fork
![pic01 :](images/pic01.jpg "pic01")

* Заполняем форму создания новой "вилки" и нажимаем **Create fork**
![pic02 :](images/pic02.jpg "pic02")

* В списке собственных репозиториев появляется ссылка на чужой репозиторий
![pic03 :](images/pic03.jpg "pic03")

* Заходим в форк чужого репозитория, нажимаем кнопку Code, на закладке HTTPS копирем адрес форка в clipboard
![pic04 :](images/pic04.jpg "pic04")

* На локальной рабочей станции, в терминале VS Code делаем clone своей версии репозитория:
git clone https://github.com/akulovokille/test345.git

* В интерфейсе VS Code (explorer) переходим в клонированный репозиторий

* Создаем новую ветку
_**git branch version2**_

* Переходим в ветку
_**git checkout version2**_

* Открываем какие-либо файлы на редактирование, вносим изменения, сохраняем локально

* Готовим изменные файлы для нового коммита
_**git add**_ .

* Делаем коммит
_**git commit**_ -m "Lines 05 and 10 have been changed"

* Отправляем свою версию в свой GitHub
_**git push**_


* На сайте GitHub нажимаем кнопку **Pull request** для отправки изменений на модерацию хозяину репозитория. 

## Работа с удаленными репозиториями локально
### Просмотр удалённых репозиториев
Для просмотра удаленных репозиториев используется команда _git remote_. В зависимости от выбранных параметров будут отображаться разные данные.
- Команда _git remote_ выведет названия доступных удалённых репозиториев
- Команда _git remote -v_ выведет пути, используемые git для работы с удаленным репозиторием

### Настройка удалённых репозиториев
Команда _git remote set-url <алиас> <url>_ заменяет ссылку для настроенного репозитория на новую.
Пример:
```
$ git remote set-url origin https://github.com/helen-kolegaeva/github_instructions.git
``` 

## Что же такое Codespaces?

Это VSCode у тебя в браузере, запущенный в заранее описанном окружении (devcontainer) или в стандартном, в который входит python, node.js, Docker и прочее. Все это крутится в облаке и бесплатно за первые 60 часов в месяц.

#### Для кого это?
Если у тебя под руками только планшет, хромбук или допотопный ноутбук, то это идеальный вариант, если надо что-то накодить или поправить в проекте, который лежит на гитхабе.

### Как попасть в Codespaces?
Достаточно просто открыть необходимый вам репозиторий и нажать на яркую зеленую кнопку code, перейти в codespaces и тыкнуть в Create codespace on main (ну или на другой бранче)

![](https://habrastorage.org/getpro/habr/upload_files/a3e/ae0/1b4/a3eae01b43a4badf32604c7e29ecc2ff.jpeg)

## Про devcontainers

Devcontainers - расширение для VSCode, которое позволяет использовать Docker-контейнер, как полнофункциональное окружение для разработки. 

### Вливание/предложение изменений в сторонний репозиторий
В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду *pull request*. Предлагать изменения на GitHub нужно в отдельной ветке. Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду *pull request*. 


## Как использовать webhooks на GitHub?
Webhooks на GitHub могут быть использованы для автоматизации различных процессов, таких как:

— оповещения о новых коммитах или pull request'ах;
— запуск сборки или тестирования вашего кода при каждом push'е в определенную ветку;
— интеграция с сервисами для непрерывной интеграции и развертывания (CI/CD);
— обновление задач в вашей системе управления проектами при изменении статусов pull request'ов и т.д.

### Чтобы создать Webhook на GitHub, нужно выполнить следующие шаги:

1. Открыть страницу настроек вашего репозитория на GitHub.
2. Выбрать пункт "Webhooks" (или "Webhooks & Services")
3. Нажать на кнопку "Add webhook"
4. В поле "Payload URL" указать URL вашего веб-сервера или сервиса, который будет получать информацию о событиях на GitHub.
5. В поле "Content type" выбрать "application/json".
6. В поле "Secret" указать секретный ключ (если нужно).
7. Выбрать список событий, которые вы хотите отслеживать и отправлять на ваш сервер.
8. Нажать на кнопку "Add webhook" для сохранения изменений.

После этого GitHub будет отправлять HTTP POST запросы на ваш сервер с информацией о всех событиях, которые вы выбрали. Вам нужно будет написать веб-хук обработчик на вашем сервере, с помощью которого вы сможете обрабатывать эти запросы и выполнять различные действия на ваш выбор.

## Что такое SSH? <a name="what_SSH"></a>

С помощью *ssh* можно подключаться к удаленным серверам, выполнять на них команды, копировать и редактировать файлы.

![](images/gitHubHead.jpg)

## Инструкция по созданию Pull Request в сторонний GitHub репозиторий

 Сначала нам необходимо склонировать изначальный репозиторий. Для этого перейдем к нему и нажмем кнопку Fork.

Далее склонированный репозиторий нужно скачать на свой компьютер.
git clone https://github.com/slaveeks/rgen

Локальный, скачанный, репозиторий имеет одну привязку к удалённому репозиторию, названную origin, которая указывает копию на GitHub, а не на оригинальный.

Downstream, то есть склонированный репозиторий, должен быть условно  курсе изменений происходящих в оригинальном репозитории, то есть в upstream. Так как разработка там продолжается. Таким образом, необходимо получить изменения (fetch) от upstream и применить к своему origin репозиторию, чтобы не было конфликтов.

Поэтому нужно создать привязку к изначальному репозиторию, чтобы проделать то, о чем сказано выше, и назвать ее любым именем, в этом примере она названа upstream, но это название обязательным не является:
git remote add upstream git://github.com/nOstr/rgen.git
git fetch upstream

После этого рекомендуется создать новую ветку и вносить изменения туда.
git checkout -b feature

Далее нужно внести изменения в сам проект при помощи коммитов.
git add .
git commit -m "My commit"

После этого небходимо отправить изменения в копию репозитория на Github.
git push origin feature


# Шпаргалка по GitHub

Добавил новую строку

##  Установка Git
GitHub предоставляет оконное приложение с графическим интерфейсом для выполнения основных операций с репозиторием, и консольную версию Git с автоматическими обновлениями для расширенных сценариев работы.

##  GitHub Desktop
https://desktop.github.com

Дистрибутивы Git для систем Linux и POSIX доступны на официальном сайте Git SCM.

Git для всех платформ
https://git-scm.com

##  Первоначальная настройка
Настройка информации о пользователе для всех локальных репозиториев

$ git config --global user.name "[имя]"

Устанавливает имя, которое будет отображаться в поле автора у выполняемых вами коммитов

$ git config --global user.email "[адрес электронной почты]"

Устанавливает адрес электронной почты, который будет отображаться в информации о выполняемых вами коммитах

##  Создание репозитория
Создание нового репозитория или получение его по существующему URL-адресу

$ git init [название проекта]

Создаёт новый локальный репозиторий с заданным именем

$ git clone [url-адрес]

Скачивает репозиторий вместе со всей его историей изменений

##  Внесение изменений
Просмотр изменений и создание коммитов (фиксация изменений)

$ git status

Перечисляет все новые или изменённые файлы, которые нуждаются в фиксации

$ git diff

Показывает различия по внесённым изменениям в ещё не проиндексированных файлах

$ git add [файл]

Индексирует указанный файл для последующего коммита

$ git diff --staged

Показывает различия между проиндексированной и последней зафиксированной версиями файлов

$ git reset [файл]

Отменяет индексацию указанного файла, при этом сохраняет его содержимое

$ git commit -m "[сообщение с описанием]"

Фиксирует проиндексированные изменения и сохраняет их в историю версий

## Коллективная работа
Именованные серии коммитов и соединение результатов работы

$ git branch

# Список именованных веток коммитов с указанием выбранной ветки

$ git branch [имя ветки]

Создаёт новую ветку

$ git switch -c [имя ветки]

Переключается на выбранную ветку и обновляет рабочую директорию до её состояния

$ git merge [имя ветки]

Вносит изменения указанной ветки в текущую ветку

$ git branch -d [имя ветки]

Удаляет выбранную ветку

# Операции с файлами
Перемещение и удаление версий файлов репозитория

$ git rm [файл]

Удаляет конкретный файл из рабочей директории и индексирует его удаление

$ git rm --cached [файл]

Убирает конкретный файл из контроля версий, но физически оставляет его на своём месте

$ git mv [оригинальный файл] [новое имя]

Перемещает и переименовывает указанный файл, сразу индексируя его для последующего коммита

Игнорирование некоторых файлов
Исключение временных и вторичных файлов и директорий

*.log
build/
temp-*
Git будет игнорировать файлы и директории, перечисленные в файле .gitignore с помощью wildcard синтаксиса

$ git ls-files --others --ignored --exclude-standard

Список всех игнорируемых файлов в текущем проекте

Сохранение фрагментов
Сохранение и восстановление незавершённых изменений

$ git stash

Временно сохраняет все незафиксированные изменения отслеживаемых файлов

$ git stash pop

Восстанавливает состояние ранее сохранённых версий файлов

$ git stash list

Выводит список всех временных сохранений

$ git stash drop

Сбрасывает последние временно сохранённыe изменения

## Просмотр истории
Просмотр и изучение истории изменений файлов проекта

$ git log

История коммитов для текущей ветки

$ git log --follow [файл]

История изменений конкретного файла, включая его переименование

$ git diff [первая ветка]...[вторая ветка]

Показывает разницу между содержанием коммитов двух веток

$ git show [коммит]

Выводит информацию и показывает изменения в выбранном коммите

## Откат коммитов
Удаление ошибок и корректировка созданной истории

$ git reset [коммит]

Отменяет все коммиты после заданного, оставляя все изменения в рабочей директории

$ git reset --hard [коммит]

Сбрасывает всю историю вместе с состоянием рабочей директории до указанного коммита.

Синхронизация с удалённым репозиторием
Регистрация удалённого репозитория и обмен изменениями

$ git fetch [удалённый репозиторий]

Скачивает всю историю из удалённого репозитория

$ git merge [удалённый репозиторий]/[ветка]

Вносит изменения из ветки удалённого репозитория в текущую ветку локального репозитория

$ git push [удалённый репозиторий] [ветка]

Загружает все изменения локальной ветки в удалённый репозиторий

$ git pull

Загружает историю из удалённого репозитория и объединяет её с локальной. pull = fetch + merge

Теперь изменения находятся в копии репозитория на GitHub в ветке feature
