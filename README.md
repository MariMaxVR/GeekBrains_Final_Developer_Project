# ***Факультет ИТ-инженер. Передовые технологии.***
## Итоговая контрольная работа студента GeekBrains Лобынцева М. С. по блоку специализации **Программист**.
![Software Developer](/images/Software%20Developer.jpg)
Информация о проекте - необходимо организовать систему учета для питомника в котором живут домашние и вьючные животные.

Дополнительная информация - все команды изначально выполнялись из под прав суперпользователя для исключения проблем или конфликтов с доступом. Можно делать и с использованием команды **sudo** из под обычного пользователя.

## **Выполение задания:**

**1. Используя команду cat в терминале операционной системы Linux, создать два файла:**
* Домашние животные (заполнив файл собаками, кошками,
хомяками)
* Вьючные животными (заполнив файл лошадьми, верблюдами и
ослами), а затем объединить их. 
* Просмотреть содержимое созданного файла.
* Переименовать файл, дав ему новое имя (Друзья человека).

![Task1](/tasks/Task1.png)

**2. Создать директорию, переместить файл туда.**

![Task2](/tasks/Task2.png)

**3. Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория.**

![Task3_1](/tasks/Task3_1.png)
![Task3_2](/tasks/Task3_2.png)

**4. Установить и удалить deb-пакет с помощью dpkg.**

![Task4](/tasks/Task4.png)

**5. Выложить историю команд в терминале ubuntu**

![Task5](/tasks/Task5.png)

**6. Нарисовать диаграмму, в которой есть родительский класс, а также дочерние классы:**
* Домашние животные (в который входят классы собаки, кошки, хомяки)
* Вьючные животные (в который входят классы лошади, верблюды и ослы)

![Task6](/tasks/Task6.png)

**7. В подключенном MySQL репозитории создать базу данных “Друзья человека”**

![Task7](/tasks/Task7.png)

**8. Создать таблицы с иерархией из диаграммы в БД**

![Task8](/tasks/Task8.png)

**9. Заполнить низкоуровневые таблицы:**
 1. Именами животных;
 2. Командами, которые они выполняют;
 3. Датами их рождения.

 ![Task9](/tasks/Task9_1.png)
 ![Task9](/tasks/Task9_2.png)
 ![Task9](/tasks/Task9_3.png)

 **10. Удалить из таблицы верблюдов, т.к. верблюдов решили перевезти в другой питомник на зимовку. Объединить таблицы лошади и ослы в одну таблицу.**

![Task10](/tasks/Task10.png)

 **11.Создать новую таблицу "молодые животные", в которую попадут все животные старше 1 года, но младше 3 лет. В отдельном столбце с точностью до месяца подсчитать возраст животных в новой таблице.**

![Task11](/tasks/Task11.png)
 
 **12. Объединить все таблицы в одну, при этом сохраняя поля, указывающие на прошлую принадлежность к старым таблицам.**

 ![Task12](/tasks/Task12.png)

 **13.Создать класс с Инкапсуляцией методов и наследованием по диаграмме.**

https://github.com/MariMaxVR/GeekBrains_Final_Developer_Project/tree/main/System/src/Model

**14. Ссылка** - [Написать программу, имитирующую работу реестра домашних животных](https://github.com/MariMaxVR/GeekBrains_Final_Developer_Project/tree/main/System/src).

В программе должен быть реализован следующий функционал:    
* Завести новое животное
* Определять животное в правильный класс
* Увидеть список команд, которое выполняет животное
* Обучить животное новым командам
* Реализовать навигацию по меню

**15**. Создайте класс [Счетчик](https://github.com/MariMaxVR/GeekBrains_Final_Developer_Project/blob/main/System/src/Controller/Counter.java), у которого есть метод add(), увеличивающий значение внутренней int переменной на 1 при нажатии "Завести новое животное". Сделайте так, чтобы с объектом такого типа можно было работать в блоке try-with-resources. Нужно бросить исключение, если работа с объектом типа счетчик была не в ресурсном try и/или ресурс остался открыт. Значение считать в ресурсе try, если при заведения животного заполнены все поля.

https://github.com/MariMaxVR/GeekBrains_Final_Developer_Project/blob/main/System/src/Controller/Counter.java

## **Результаты прохождения тестирования:**
![Certificate](/images/Certificate.png)
![TestResult](/images/TestResult.png)