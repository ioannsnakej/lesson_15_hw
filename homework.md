1. Установите и настройте Nginx. Создайте html-страничку, где будет указана
ваша фамилия и тема урока. Настройте конфигурацию nginx для отображения
страницы по ссылке http://tms.by

  nginx был установлен в предыдущих домашках:

  <img width="1257" height="484" alt="image" src="https://github.com/user-attachments/assets/60ff9a6e-d424-4eee-a97d-033638c91abf" />

  создал index.html в /var/www/lesson_15_hw:

  <img width="933" height="591" alt="image" src="https://github.com/user-attachments/assets/048179bf-0a13-442b-90a3-a5360e38fae4" />

  создаю nginx config, проверяю, делаю символическую ссылку:

  <img width="927" height="554" alt="image" src="https://github.com/user-attachments/assets/af7ab481-314a-4725-9198-fe10aeadb5fa" />

  добавил домен tms.by в файл /etc/hosts

  <img width="781" height="739" alt="image" src="https://github.com/user-attachments/assets/3b2474e0-9c03-4370-98be-d5bc584d9349" />

  перезапускаю nginx, через sudo nginx -s reload:

  <img width="943" height="659" alt="image" src="https://github.com/user-attachments/assets/25d5d963-3f2d-4ecf-adfd-4155e96b07dc" />


  пробую заходить:

  <img width="688" height="85" alt="image" src="https://github.com/user-attachments/assets/c63396a9-1c05-4fec-a3f3-cca69455a50a" />


  




  
