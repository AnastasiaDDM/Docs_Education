# Описание интерфейса IVisit
Интерфейс предназначен для работы с методами класса [Visit](./Visit.md "Класс Visit")

## Реализация интерфейса

* **add**(Visit: Visit): String – функция, добавляющая посещение в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  посещение из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Visit: Visit): String – функция, редактирующая данные о посещении;
* **findAll**(  Start:	DateTime, End:	DateTime, visitNumber: Int, Date:	DateTime,  editDate:	DateTime, delDate:	DateTime,  Visit: Bool,  Student: Student,  Course: Course, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Visit >   – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с некоторыми входными параметрами sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.  
