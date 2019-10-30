# Описание интерфейса IGrade
Интерфейс предназначен для работы с методами класса [Grade](./Grade.md "Класс Grade")

## Реализация интерфейса

* **add**(Grade: Grade): String – функция, добавляющая  оценку в базу данных;
* **del**( ID: Int): String –  функция, удаляющая оценку из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Grade: Grade): String – функция, редактирующая данные об оценке;
* **findAll**(  Start:	DateTime, End: DateTime, visitNumber: Int, Date:	DateTime,  editDate: DateTime, delDate:	DateTime,  Gradeot: Int,  Gradedo: Int,  Student: Student,  Course: Course, Theme: String, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Grade >  – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с некоторыми входными параметрами sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.  



