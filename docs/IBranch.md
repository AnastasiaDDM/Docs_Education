# Описание интерфейса IBranch
Интерфейс предназначен для работы с методами класса [Branch](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **getWorkers** ( Branch: ID: Int ):List< Worker > – функция, получающая список работников этого филиала;
* **getContracts** (Branch: Branch): List< Contract > – функция, получающая список договоров, заключенных в этом филиале;
* **getCourses**(Branch: Branch): List< Course > – функция, получающая список курсов, которые обучаются в этом филиале;
* **getCabinets**(Branch: Branch): List< Cabinet > – функция, получающая список кабинетов этого филиала;
* **add**(Branch: Branch): String – функция, добавляющая филиал в базу данных;
* **del**( ID: Int): String –  функция, удаляющая филиал из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Branch: Branch): String – функция, редактирующая данные о филиале;
* **profit**(Branch: Branch,  Start: Datetime, End: Datetime): Double – функция, подсчитывающая прибыль филиала;
* **revenue**(Branch: Branch, Start: Datetime, End: Datetime): Double – функция, подсчитывающая выручку филиала;
* **findAll**( editDate:	DateTime, delDate:	DateTime, ID: Int, Name: String, Address: String, DirectorBranch: String,  sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Branch > – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, Name – название филиала, Address, DirectorBranch, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.  Функция возвращает список всех найденных филиалов, удовлетворяющих условиям. Если введены параметры для сортировки, то данные будут отсортированы.