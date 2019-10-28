# Описание интерфейса IPay
Интерфейс предназначен для работы с методами класса [Pay](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **add**(Pay: Pay): String – функция, добавляющая оплату в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  оплату из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Pay: Pay): String – функция, редактирующая данные об  оплате;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, payNumber: Int, Contract: Contract, Date: DateTime, Payment: Double, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Pay > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами payNumber – количество выводимых оплат, Contract – договор, по которому требуется получить оплаты, Date, Payment – оплата, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.  
