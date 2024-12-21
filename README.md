# Les17
Docker-compose

1. Встановив Docker на системі:
![Docker_install](https://github.com/user-attachments/assets/67fd134f-7d8b-41bb-8331-efeb752bc7ba)

2. Створив файл docker-compose.yml з трьома сервісами webserver, database та cache.
3. Запустив всі сервіси за допомогою команди docker-compose up -d 
![01](https://github.com/user-attachments/assets/09f92ff6-0a49-4044-bec2-602b36f6bedd)
та перевірив стан їх роботи командою docker ps.
![03](https://github.com/user-attachments/assets/f90757d9-d4c1-4ba7-b872-ce2dc03604af)

Відкрив http://localhost/ в браузері.
![02](https://github.com/user-attachments/assets/4f122556-8af2-43eb-9ffd-e93e0285b3c5)

4. Перевірив мережі та томи за допомогою команд docker network ls та docker volume ls.
![04](https://github.com/user-attachments/assets/ba0c6a81-43dc-4bb4-b8be-6a8ccd214a40)

5. Для запуску трьох екземплярів вебсервера використав команду docker-compose up -d --scale webserver=3.
Як результат запустилось 3 webservers, з можливістю відкрити сторінки за адресами:
http://localhost:51452/, http://localhost:51453/, http://localhost:51454/.
![05](https://github.com/user-attachments/assets/1eb118e3-0ffd-4e47-9b39-45465bad249a)


