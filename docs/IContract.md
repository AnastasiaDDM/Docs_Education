# Описание интерфейса IContract
Интерфейс предназначен для работы с методами класса [Contract](./Contract.md "Класс Contract")

## Реализация интерфейса

* **add**(Contract: Contract): String – функция, добавляющая договора в базу данных;
* **del**( ID: Int): String –  функция, удаляющая договор из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Contract: Contract): String – функция, редактирующая данные о договоре;
* **addPay**(ID: Int, Payment: Double): String – функция добавляет оплату по этому договору;
* **Cancellation**(ID: Int): String – функция расторжения договора, меняются соответствующие поля в базе данных;
* **findAll**( editDate:	DateTime, delDate:	DateTime, contNumber: Int, ID: Int, Date: DateTime, Client: Student, Manager: Manager, Branch: Branch,  Course: Course, Cost: Double,  starttime, endtime, sorting : String, ASKorDESK : String,  count : Int, page : Int): List<Contract> – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, Date – дата заключения договора, Client, Manager – менеджер, который заключил договор, Branch – филиал, в котором заключили договор, Course – курс, на который заключен договор, Cost – цена за курс, starttime – нижняя граница выборки данных по дате, endtime – верхняя граница выборки данных по дате, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.


