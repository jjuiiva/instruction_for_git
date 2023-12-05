# Описание проекта **'Как создать репозиторий в Git'**
## Инструкция:
1) Научиться пользоваться терминалом:  
- Перемещаться по директориям;  
- Создавать файлы;  
- Удалять файлы;  
2) Создать папку для репозитория во внутреннем хранилище данных;  
3) Зайти в эту папку и инициализировать ее как главную ветку с помощью git;
4) Создать удаленный репозиторий на платформе GitHub;  
5) Скопировать ssh ключ удаленного репозитория;  
6) Использовать в терминале команду: 
```
git remote add [имя новой глав. ветки] [ssh удаленного репозитория]
```
  
7) Проверить соединение репозиториев с помощью команды:
```
git remote -v
```
Должно повиться сообщение:
```
[имя ветки] [ssh удаленного репозитория] (fetch)
[имя ветки] [ssh удаленного репозитория] (push)
```
8) Принудительно соединить репозитории с помощью команды:
```
git push -u [имя ветки] [master/main]
```
Далее можно будет использовать сокращенную форму команды для отправки файлов на сервер:
```
git push
```
