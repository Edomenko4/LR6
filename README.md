**Отчет по лабораторной работе №6** 

**По курсу: Основы программирования**

**Выполнил студент гр. 4916 Д.А. Едоменко**


**Ход работы:**

На сайте GitHub сделал копию лабораторной работы https://github.com/Kurtyanik/LR6/

![Копированный репозиторий](Screenshots/Screenshot1.png)

Далее, введя имя пользователя и email, настроил клиент

![Персональные данные](Screenshots/Screenshot2.png)

С помощью команды cd Desktop/инфа/lab6  перешёл в созданную папку lab6

Использовал команду git init чтобы инициализировать гит в данной папке

![git init](Screenshots/Screenshot3.png)

Командой _git remote add origin_ связал папку с удалённым репозиторием и командой _git clone_ клонировал удаленный репозиторий на компьютер на сайте GitHub

![git remote add origin](Screenshots/Screenshot4.png)

Через интерфейс GitHub добавил новый файл _fail1.txt_ в удалённый репозиторий и добавил его в ветку **master**

![Новый файл](Screenshots/Screenshot5.png)


Используя команду _git pull origin master_ загрузил изменения из удалённого репозитория в локальный

![git pull](Screenshots/Screenshot6.png)


Командой _git log_ получил список коммитов

![git log](Screenshots/Screenshot7.png)

Используя _git show_ получил  информацию о последнем изменении

![git show](Screenshots/Screenshot8.png)

Командой _git checkout -t branch1_ переключился на ветку **branch1**

![git checkout](Screenshots/Screenshot9.png)


Попытался сделать слияние веток **master** и **branch1**, но получил ошибку. В итоге, вручную изменил содержание файла mergefile.txt, устранив ошибку слияния и выполнил коммит

![Изменил файл](Screenshots/Screenshot10.png)

Выполнил слияние веток **master** и **branch1** с помощью команды _git merge branch1_ и удалил ветку **branch1** командой _git branch -d branch1_

![Слияние и удаление](Screenshots/Screenshot11.png)

Занес всё в удалённый репозиторий командой _git push origin master_ 

![Push1](Screenshots/Screenshot12.png)

Добавил два новых файла. один из файлов на первом скриншоте не видно, так как по своей глупости я сделал сриншот уже после отката одного из файлов

![File1,2](Screenshots/Screenshot13.png)

![File1,2 git log](Screenshots/Screenshot14.png)

Командой _git reset --hard HEAD~1_ выполнил откат последнего коммита, а именно добавления файла fail3.txt и занес изменённую ветку в удаленный репозиторий

![hard](Screenshots/Screenshot15.png)


Используя команду _git checkout -b account_ создал новую ветку **account**

![report](Screenshots/Screenshot16.png)

С помощью команды _git add ._ подготовил все новые файлы в папке lab6 к добавлению и занес в удаленный репозиторий

![git add](Screenshots/Screenshot18.png)

![git push](Screenshots/Screenshot19.png)

Оформил отчёт в файле README.md, используя блокнот

![Readme](Screenshots/Screenshot20.png)

Лог команд из папки **.git/logs**

![Logs](Screenshots/Screenshot21.png)

Конечный результат команды _git log_

![git logs](Screenshots/Screenshot22.png)

![git logs](Screenshots/Screenshot22.png)

Все скриншоты лежат в папке **Screenshots**
