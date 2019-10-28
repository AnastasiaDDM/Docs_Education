# Описание интерфейса ITimetable
Интерфейс предназначен для работы с методами класса [Timetable](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **add**(Timetable: Timetable): String – функция, добавляющая элемент расписания в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  элемент расписания из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Timetable: Timetable): String – функция, редактирующая данные об элементе расписания;
* **addTeacher**(ID: Int, IDWorker: Int ): String –  функция, добавляющая преподавателя к этому элементу расписания;
* **delTeacher**(ID: Int, IDWorker: Int ): String –  функция, удаляющая преподавателя из этого элемента расписания;
* **findAll**(  Timetable: Timetable, Start: Datetime, End: Datetime,  editDate:	DateTime, delDate:	DateTime,  Course: Course, Cabinet: Cabinet, Teacher: Worker): List< Timetable >  – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с некоторыми входными параметрами sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.