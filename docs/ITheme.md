# Описание интерфейса ITheme
Интерфейс предназначен для работы с методами класса [Theme](https://github.com/saramampco/oop/blob/master/docs/Client.md)

## Реализация интерфейса

* **add**(Theme: Theme): String – функция, добавляющая тему в базу данных;
* **del**( ID: Int): String –  функция, удаляющая  тему из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Theme: Theme): String – функция, редактирующая данные об  теме;
* **getGrade** (ID: Int): List< Grade > – функция, получающая список оценок по этой теме;
* **findAll**(  Start:	DateTime, End:	DateTime, themeNumber: Int, Date:	DateTime,  editDate:	DateTime, delDate:	DateTime,  Course: Course, Theme: String, sorting : String, ASKorDESK : String,  count : Int, page : Int): List< Theme >  – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с некоторыми входными параметрами sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию, count – количество.