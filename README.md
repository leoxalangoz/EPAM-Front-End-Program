# EPAM-Front-End-Program

Front-End Self-Paced Online Program EPAM

Основные моменты настройки Git Вы можете скачать git здесь: 
http://git-scm.com/downloads 
Установите Git с настройками по умолчанию. Генерация пары ключей ssh:

ssh-keygen -t rsa –C «leox.alangoz@gmail.com»
Публичный ключ (id_rsa) необходимо отправить владельцу репозитория для получения прав на работу. Или залить в настройки профиля в bitbucket/github/gitlab. Настройки имени пользователя и электронной почты: 
git config --global user.name "Olena Luganska" 
git config --global user.email "leox.alangoz@gmail.com"

$ cd /d/Downloads/EDU/GIT/EPAM-Front-End-Program
$ git clone git@github.com:leoxalangoz/Front-End-Online-Program.git 
$ cd /d/Downloads/EDU/GIT/Front-End-Online-Program 
$ git remote -v 
$ git add . 
$ git commit -m "add something"
  git push
$ git status


добавить файлы если сделаны изменения на удаленке
git log
git pull

!!!ЗАПУСК ГРАФИЧЕСКОГО ИНТЕРФЕЙСА GIT
$ git gui&

работаем
