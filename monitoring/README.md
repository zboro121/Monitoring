# Monitoring
GIT - stworzenie repozytorium
https://github.com/zboro121/Monitoring.git

Skonfigurowanie środowiska
Niezbedne narzedzia Linux - Ubuntu
~$ apt update
~$ apt install python3-pip python3-venv git sqlite3
~$ pip3 install virtualenv

Biblioteki
~$ apt install  ipython3-qtconsole python3-tk python3-sip python3-pyqt5
~$ sudo pip3 install django

Katalog główny projektu "Monitoring"
/home/ubuntu/monitoring/

Tworzenie środowiska do pracy
~$ virtualenv -p python3 pve3
~$ source pve3/bin/activate
(pve3) ~$ pip install Django==1.11.2

Tworzenie proejktu Django o nazwie monitoring
(pve3) ~/$ django-admin.py startproject monitoring
(pve3) ~$ cd monitoring
(pve3) ~$ python manage.py migrate

git 