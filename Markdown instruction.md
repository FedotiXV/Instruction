# 1. Команды для GIT
*Создание репризитория:*
```
git init
```
*Получение информации от git о его текущем статусе:*
```
git status
```
*Добавление файла к следуюшему коммиту:* 
```
git add
```
*Создание коммита:*
```
git commit -m <Название файла>
```
*Вывод на экран истории всех комммитов с их кодами:*
```
git log
```
*Просмотр других коммитов (версий документа):*
```
git checkout
```
*Возвращение к актуальной версии и продолжить работу:*
```
git checkout master
```
*Разница между текущим файлом и заакоммиченным (сохранненным) файлом:*
``` 
git diff
```
*Смотреть разницу между файлами:*
```
git diff 1234 5678
```
*Собрать рядом все коммиты (собрать рядом в список все версии файлов):*
```
git log --oneline
```
*Просмотр веток:*
```
git branch
```
*Добавление новой ветки:*
```
git branch <Название ветки
```
*Слияние двух веток в одну:*
```
git merge <Название ветки которую хотим добавить в основную>
```
*Удаление ветки:*
```
git branch -d <Название ветки>
```
*Просмотр полного списка и действий веток:*
```
git log --graph
```
*Очистка поля в терминале:*
```
clear
```
# 2. Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом необходимо обрамить его звездочками (*) или знаком нижнее подчеркивание (_). Например *Вот так*.

Чтобы выделить текст полужирным, необходимо его обрамить двойными звездочками (**) или двойным знаком нижнее подчеркивание (__). Например **Вот так**.

Альтернативные способы выделения текста жирным или курсивом нужны для тоого, чтобы мы могли совмещать оба этих способа. Например, _текст может быть выделен курсивом и при этом быть **полужирным**_

Если хочешь написать загаловок с большим буквами поставь вначале #

## Списки
Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+). Например вот так:
* Элемент 1
* Элемент 2
* Элемент 3 
+ Элемень 4 с плюсом


Чтобы добавить нумерованные списки, неободимо пункты просто пронумеровать. Например вот так:
1. Первый пункт
2. Второй пункт 
3. Третий пункт

## Работа с изображениями 

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это Мальтипу!](Мальтипу.jpg)

## Ссылки
Текст [пример ссылки](http.example.com "ССылка подсказка")

Чтобы написать такую ссылку, НУЖНО в квадратных скобках написать пример ссылки, даллее в круглах скобка написать сайт (http.yes.com потом открыть ковычки - добавить подпись и закрыть ковычки)

## Работа с таблицами

## Цитаты 
>Первый уровень цитирования
>>Второй уровень цитирования 

Чтобы написать цитирование нужно поставить 1 знак > (перед началом написания текста), или чтобы написать второй уровень цитирования, нужно поставить 2 знака>> (перед началом написания текста)
## Заключение