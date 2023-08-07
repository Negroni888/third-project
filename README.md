# Список команд

cd ~ Вернуться в корневую директорию


cd .. Вернуться на уровень выше


ls Вывод всех файлов в папке


git commit -m Создание коммита с комментарием

mkdir Создание папки

touch Создание файла


rm Удаление файла


git remote add origin https://github.com/Negroni888/third-project.git Связать репозитории на ПК с GitHub


git remote -v Убедиться что репозитории связаны


git push отправить изменения на удалённый репозиторий

git log просмотреть историю сделанных коммитов


# Как добавить изменения в GitHub
1. Внести изменения в тексовый файл и сохранить

2. cd *имя файла*

3. git add --all

4. git commit -m 'Комментарий'

5. git push

6. git status

# Информация о логах, хэшах и статусе файлов

git status Вывод информации о любом объекте в Git

# Mermaid-схема

```mermaid
graph LR;
  untracked -- "git add" --> staged;
  staged    -- "???"     --> tracked/comitted;

%% стрелка без текста для примера: 
  A --> B;
```