# LR6
## Лабораторная работа №6

### ***Порядок выполнения работы***
1. Создать аккаунт на сайте GitHub.

![Рисунок 1](LR_screenshots/0.JPG)

2. Сделать копию (Fork) в личное хранилище из 
```
https://github.com/Kurtyanik/LR6/
```

![Рисунок 3](LR_screenshots/2.JPG)

3. Установить Git 
4. После установки настроить клиент git, введя имя пользователя (Группа 
Фамилия И.О.) и email.

![Рисунок 3](LR_screenshots/1.jpg)

5. Клонировать свой личный удалённый репозиторий на компьютер.

![Рисунок 3](LR_screenshots/3.jpg)

![Рисунок 3](LR_screenshots/4.jpg)

6. Добавить файл через интерфейс GitHub. Подтянуть изменения в 
локальный репозиторий.

![Рисунок 3](LR_screenshots/5.jpg)

![Рисунок 3](LR_screenshots/6.jpg)

![Рисунок 3](LR_screenshots/7.jpg)

7. Получить историю операций для каждой из веток.

![Рисунок 3](LR_screenshots/8.jpg)

8. Просмотреть последние изменения.

![Рисунок 3](LR_screenshots/9.jpg)

![Рисунок 3](LR_screenshots/10.jpg)

9. Выполнить слияние в ветку master, разрешив конфликт (можно 
использовать специальные редакторы или графический интерфейс git).

![Рисунок 3](LR_screenshots/11.jpg)

![Рисунок 3](LR_screenshots/12.jpg)

![Рисунок 3](LR_screenshots/13.jpg)

![Рисунок 3](LR_screenshots/14.jpg)

![Рисунок 3](LR_screenshots/15.jpg)

10. Удалить побочную ветку после успешного слияния.

Удаление в локальном репозитории.

![Рисунок 3](LR_screenshots/16.jpg)

Удаление в удаленном репозитории.

![Рисунок 3](LR_screenshots/17.jpg)

![Рисунок 3](LR_screenshots/18.jpg)

11. Сделать изменения и зафиксировать их, оставляя комментарии, 
несколько раз.

Первые изменения

![Рисунок 3](LR_screenshots/19.jpg)

Вторые изменения

![Рисунок 3](LR_screenshots/20.jpg)

12. Сделать откат коммита.

![Рисунок 3](LR_screenshots/21.jpg)

13. Создать ветку для отчёта.

![Рисунок 3](LR_screenshots/22.jpg)

# Лог команд
```
git config --global user.name
git config --global user.email
git clone
git pull
git checkout <name branch>
git log --all --graph –decorate
git log --oneline --graph –all
git show
git merge <name branch>
git status
git add <file>
git add .
git commit -m "text commita"
git branch -d <name branch>
git push -d origin <name branch>
git reset --hard <hash commit>
git push
git push origin <name branch>
```