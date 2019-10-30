# Описание интерфейса ICabinet
Интерфейс предназначен для работы с методами класса [Cabinet](./Cabinet.md "Класс Cabinet")

## Реализация интерфейса


* **add**(Cabinet:Cabinet): String – функция, добавляющая кабинет в базу данных;
* **del**( ID: Int): String –  функция, удаляющая кабинет из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Cabinet:Cabinet): String – функция, редактирующая данные о кабинете;
* **getTimetable**(ID: Int, Start: Datetime, End: Datetime): List< Timetable > – функция, получающая расписание данного кабинета;
* **getFree**( Start: Datetime, End: Datetime, Branch: Branch): List< Cabinet >– функция, получающая список свободных кабинетов в конкретном филиале  на заданный промежуток времени;
* **findAll**( editDate: DateTime, delDate: DateTime, cabNumber: Int, ID: Int, Number: String, Branch: Branch, Capacityot: Int,  Capacitydo: Int, sorting : String,  ASKorDESK : String,  count : Int, page : Int): List< Cabinet > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, Number, Branch – филиал, в котором находятся кабинеты, Capacityot – начальная вместимость кабинета, Capacitydo – конечная вместимость кабинета, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.  Функция возвращает список всех найденных кабинетов, удовлетворяющих условиям. Если введены параметры для сортировки, то данные будут отсортированы.


