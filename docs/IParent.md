# Описание интерфейса IParent
Интерфейс предназначен для работы с методами класса [Parent](./Parent.md "Класс Parent")

## Реализация интерфейса

* **add**(Parent: Parent): String – функция, добавляющая  ответственное лицо в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  ответственное лицо из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Parent: Parent): String – функция, редактирующая данные об  ответственном лице;
* **getStudents**(ID:Int ): List< Student > –  функция, получающая список учеников этого отв. лица;
* **addStudent**(ID: Int, IDStudent: Int ): String –  функция, добавляющая ученика к этому отв. лицу;
* **delStudent**(ID: Int, IDStudent: Int ): String –  функция, удаляющая ученика из под ответственности этого отв. лица;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, paNumber: Int, ID: Int, FIO: String, Phone: String, Student: Student, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Parent > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с некоторыми входными параметрами sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.  