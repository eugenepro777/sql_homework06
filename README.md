# Урок 6

## **SQL – Транзакции. Временные таблицы, управляющие конструкции, циклы**

### **Основное ДЗ**

- Создайте функцию, которая принимает кол-во сек и формат их в кол-во дней, часов, минут и секунд.  
  *Пример: 123456 ->'1 days 10 hours 17 minutes 36 seconds '*

  ![Вариант решения](pictures/format_seconds1.PNG "Пример решения для 123456")

  ![Вариант решения](pictures/format_seconds2.PNG "Пример решения для 23456")

  ![Вариант решения](pictures/format_seconds3.PNG "Пример решения для 2234568")

---  

- Выведите только четные числа от 1 до 10 (Через цикл).  
  *Пример: 2,4,6,8,10*

    ![Вариант решения](pictures/even_numbers.PNG "Четные числа от 1 до 10")

---

### **Дополнительное задание: (для ВК: [по ссылке](https://www.notion.so/c448e32ae1344f22b1deae7f42c8b57f))**

- Создать процедуру, которая решает следующую задачу
Выбрать для одного пользователя 5 пользователей в случайной комбинации, которые удовлетворяют хотя бы одному критерию:
  - а) из одного города
  - б) состоят в одной группе
  - в) друзья друзей

    ![Вариант решения](pictures/random_5_users.PNG "5 пользователей в случайной комбинации")

- Создать функцию, вычисляющей коэффициент популярности пользователя (по количеству друзей).

  ![Вариант решения](pictures/popularity1.PNG "Для пользователя с id=1")

  ![Вариант решения](pictures/popularity7.PNG "Для пользователя с id=7")

- Создайте хранимую функцию hello(), которая будет возвращать приветствие, в зависимости от текущего времени суток:
  - С 6:00 до 12:00 функция должна возвращать фразу "Доброе утро";
  - с 12:00 до 18:00 функция должна возвращать фразу "Добрый день";
  - с 18:00 до 00:00 — "Добрый вечер";
  - с 00:00 до 6:00 — "Доброй ночи".
  
    ![Вариант решения](pictures/greeting.PNG "Для пользователя с id=7")

    ![Вариант решения](pictures/greeting2.PNG "Для пользователя с id=7")

---
  
[В начало &#11014;](#урок-6)
