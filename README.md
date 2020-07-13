Это тестовое задание для Doubletapp.
 
Это приложение на Django, у которого есть API и админка, описанные в ТЗ. 

Чтобы развернуть приложение у себя на машине нужно:
1. Установить docker-compose версии 1.21.2
2. Выполнить в консоли sudo docker-compose start в корневой директории проекта.
3. Выполнить в консоли sudo docker-compose run web python3 manage.py makemigrations
4. Выполнить в консоли sudo docker-compose run web python3 manage.py migrate
5. Выполнить в консоли sudo docker-compose up

Чтобы войти в админку приложения необходимо ввести:

user: root

password: password
