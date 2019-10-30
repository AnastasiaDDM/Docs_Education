# Описание интерфейса IWorker
Интерфейс предназначен для работы с методами класса [Worker](./Worker.md "Класс Worker")

## Реализация интерфейса

* **add**(Worker: Worker): String – функция, добавляющая работника в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  работника  из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Worker: Worker): String – функция, редактирующая данные о работнике;
* **getContracts**(ID:Int ): List< Contract > –  функция, получающая список договоров, заключенных этим менеджером;
* **getTimetable**(ID: Int, Start: Datetime, End: Datetime): List< Timetable > – функция, получающая расписание данного преподавателя;
* **Salary**( ID: Int, Start: Datetime, End: Datetime, Rate: Double): Double – функция, считающая зарплату преподавателя;
* **addPay**(ID: Int, Payment: Double): String – функция, добавляющая оплату за занятие;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, worNumber: Int, ID: Int, FIO: String, Position: String, Type: Bolean, Branch: Branch, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Worker >  – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами  ID, FIO, Position - должность, Type – тип работника (true –  преподаватель, false – управляющая должность), Branch, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.