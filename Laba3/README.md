1. 

mrzara@mrzara-VirtualBox:~$ cd Labs

mrzara@mrzara-VirtualBox:~/Labs$ mkdir Laba3

mrzara@mrzara-VirtualBox:~/Labs$ cd Laba3

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ ls

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ pipenv --python 3.7

Creating a virtualenv for this project...

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ pipenv install django

Installing django...

Adding django to Pipfile's [packages]...

✔ Installation Succeeded 


2.

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ ls

manage.py  my_site  Pipfile  Pipfile.lock

3.

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ pipenv run python manage.py runserver

Watching for file changes with StatReloader

Performing system checks...

System check identified no issues (0 silenced).

You have 17 unapplied migration(s). Your project may not work properly until you apply the migrations for app(s): admin, auth, contenttypes, sessions.

Run 'python manage.py migrate' to apply them.

October 25, 2019 - 17:51:20

Django version 2.2.6, using settings 'my_site.settings'

Starting development server at http://127.0.0.1:8000/

Quit the server with CONTROL-C.

4.
mrzara@mrzara-VirtualBox:~/Labs/Laba3$ git add .

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ git commit -m "Laba 3.Django"

5.
mrzara@mrzara-VirtualBox:~/Labs/Laba3$ pipenv run python manage.py startapp main

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ mkdir main/templates &&

6.
mrzara@mrzara-VirtualBox:~/Labs/Laba3$ mkdir main/templates &&

> touch main/templates/main.html main/urls.py

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ ls

db.sqlite3  main  manage.py  my_site  Pipfile  Pipfile.lock

mrzara@mrzara-VirtualBox:~/Labs/Laba3$ ls

db.sqlite3  main  manage.py  my_site  Pipfile  Pipfile.lock

7,8,9 у файлах

10 перевірив чи правює + все ок

11.pipenv install requests

12.13 є файли

14 пушнув лог
