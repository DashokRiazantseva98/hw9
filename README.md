# hw9
Во время выполнения задания я использовала программу Notepad++.
## 1. Удалить все пустые строки.

Мной было использовано регулярное выражение \n\r, которое я потом заменила на *\0*, и удалила все пустые строки. 

![](https://github.com/DashokRiazantseva98/hw9/blob/master/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9%201.png)

## 2. Найти всех князей и города, имя и название которых оканчивается на "слав".

Для выполнения этого задания я использовала регулярное выражение [А-Я]+\w+слав+\w*. Получилось *592* вхождения.

![](https://github.com/DashokRiazantseva98/hw9/blob/master/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9%202.png)

## 3. Найти все упоминания Новгорода.

Я использовала регулярное выражение (Новѣ?город[а-я]?|Новъ?город[а-я]?|Новгородц[а-я]?|Новагород[а-я]?|Новугород[а-я]?|Новгород[а-я]?). Получилось *59* вхождений.

![](https://github.com/DashokRiazantseva98/hw9/blob/master/%D0%91%D0%B5%D0%B7%D1%8B%D0%BC%D1%8F%D0%BD%D0%BD%D1%8B%D0%B9%203.png)
