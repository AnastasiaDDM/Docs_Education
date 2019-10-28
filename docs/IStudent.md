# Описание интерфейса IStudent
Интерфейс предназначен для работы с методами класса [Student](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **add**(Student: Student): String – функция, добавляющая ученика в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  ученика из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Student: Student): String – функция, редактирующая данные об  ученике;
* **getContracts** (ID: Int): List< Contract > – функция, получающая список договоров, заключенных с этим учеником;
* **getCourses**(ID: Int, Finished: Bolean): List< Course > – функция, получающая список курсов, на которых обучается ученик;
* **getTimetable**(ID: Int, Start: Datetime, End: Datetime): List< Timetable > – функция, получающая расписание данного ученика;
* **getParent**(ID:Int ): List< Parent > –  функция, получающая список отв. лиц этого ученика;
* **addParent**(ID: Int, IDParent: Int ): String –  функция, добавляющая отв. лицо;
* **delParent**(ID: Int, IDParent: Int ): String –  функция, удаляющая отв. лицо;
* **getDebt**( ID: Int, IDContract: Int): Double  – функция, получающая задолженность этого студента по договору;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, stNumber: Int, ID: Int, FIO: String, Phone: String, Contract: Contract, Course: Course, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Student > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, FIO, Phone, Contract, Course, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.