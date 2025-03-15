Лабораторная 1:

1) Выберите из таблицы orders все заказы

   
![aa1](https://github.com/user-attachments/assets/6895b211-4d76-47ef-8531-b396e71ae814)



2) Выберите из таблицы orders все заказы кроме новых. 
У новых заказов status равен "new". Использовать in
   ![aa2](https://github.com/user-attachments/assets/107e5f52-585a-4a12-b815-426b646b5be3)



3) Выберите из таблицы orders все новые и отмененные заказы. У отмененных заказов status равен "cancelled". У новых заказов status равен "new".

  ![aa3](https://github.com/user-attachments/assets/5bd3e56d-8010-4415-aa37-b1bfc2fd5840)


4) Выберите из таблицы orders все заказы содержащие более 3 товаров (products_count).
Вывести нужно только номер (id) и сумму (sum) заказа.

![aa4](https://github.com/user-attachments/assets/bc359565-43da-44fc-aa5d-09724e8f50fb)




Лабораторная 2:

1) Выберите из таблицы orders 3 самых дешевых заказа за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![aa5](https://github.com/user-attachments/assets/98ec3abd-ef83-4218-acf6-769ec1560f37)



2) Выберите из таблицы orders 2 самых дорогих заказов за всё время.
Данные нужно отсортировать в порядке убывания цены.
Отмененные заказы не учитывайте.

![aa6](https://github.com/user-attachments/assets/2d085b62-a785-4542-bced-cc5490fa34c5)



3) Добавьте в таблицу orders данные о новом заказе стоимостью 8000 рублей. В заказе 4 товара (products).

   ![image](https://github.com/user-attachments/assets/f0b7fe57-6c94-441e-9ff2-91ee55aec109)

![image](https://github.com/user-attachments/assets/cb894435-f384-49df-9a1a-35296fff1a52)


4) Добавьте в таблицу products новый товар — «VR-очки», стоимостью 70000 рублей в количестве (count) 2 штук.

   ![image](https://github.com/user-attachments/assets/b9d23143-30df-4c85-8e4a-1ba151d82b4f)

![image](https://github.com/user-attachments/assets/83cdec71-1cbc-4171-98df-3f4edd185509)

5) В таблицу products внесли данные с ошибкой, вместо "PS5" в наименовании написали IMAC. Исправьте ошибку.

   ![image](https://github.com/user-attachments/assets/f903e5f0-fe00-4fc5-846d-8d425beb2343)

   ![image](https://github.com/user-attachments/assets/267b0963-015c-47ea-b9c4-fa411901e773)

Шпоргалки, ну да: 
INSERT INTO table (column1, column2) VALUES (value1, value2);
 Добавление одной записи
 
INSERT INTO table (column1, column2) VALUES (value11, value12), (value21, value22), ...
 Добавление нескольких записей
 
INSERT INTO table1 (column1, column2) SELECT (col1, col2) FROM table2;
 Добавление записей из другой таблицы
 
UPDATE table1 SET column1 = new value;
 Обновление поля во всех записях
 
UPDATE table1 SET column1=new_value column2=new_value WHERE condition;
 Обновление поля во записях, соответствующих условию
 
 DELETE FROM table; Удаление всех записей
 
 DELETE FROM table WHERE condition; Удаление записей, соответствующих условию

 Лабораторная 3:
 
 1) Создайте таблицу users для хранения информации о пользователях сайта.
В таблице должны быть следующие поля:

id – идентификатор, целое положительное;
email – адрес электронной почты, строка не более 100 символов;
date_joined – дата регистрации (достаточно хранить дату, без времени)
last_activity – дата и время последней активности (с точностью до секунд).

![image](https://github.com/user-attachments/assets/bfb871ef-8642-4f4c-b120-3d748ef0f204)

![image](https://github.com/user-attachments/assets/34dfe760-516b-496d-999a-4790d0fe67e0)

2) Создайте таблицу calendar для хранения календаря посетителей.
В таблице должны быть следующие поля:

id – идентификатор записи в календаре, целое положительное;
user_id – идентификатор пользователя, целое положительное;
doctor_id – идентификатор доктора, целое положительное;
visit_date – дата и время визита (точность до секунд).

![image](https://github.com/user-attachments/assets/35dd0c80-f95e-4a2d-9646-9fd7d25c1ec9)

![image](https://github.com/user-attachments/assets/7e754d02-e252-4d88-889b-3fc1008915a6)

