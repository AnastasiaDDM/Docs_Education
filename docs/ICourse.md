# Описание интерфейса ICourse
Интерфейс предназначен для работы с методами класса [Course](./Course.md "Класс Course")

## Реализация интерфейса

* **add**(Course: Course): String – функция, добавляющая  курс в базу данных;
* **del**( ID: Int): String –  функция, удаляющая курс из программы и в базе данных меняющая некоторые значения полей;
* **edit**(Course: Course): String – функция, редактирующая данные о курсе;
* **getStudents**(ID: Int): List< Student > – функция, получающая список учеников этого курса;
* **getTimetable**(ID: Int,  Start: Datetime, End: Datetime): List< Timetable > – функция, получающая расписание этого курса;
* **addTeacher**(ID: Int,  Worker: Worker): String – функция добавления преподавателя на курс;
* **delTeacher**(ID: Int, IDWorker: Int): String – функция удаления преподавателя с курса;
* **addStudent**(ID: Int, Student: Student): String – функция добавления ученика на курс;
* **delStudent**(ID:Int, IDStudent: Int): String – функция удаления ученика с курса;
* **findAll**(  editDate:	DateTime, delDate:	DateTime, courseNumber: Int, ID: Int, NameGroup: String, Costot: Double, Costdo: Double, Teacher: Worker, Type: Type, Branch: Branch, Start: DateTime, End: DateTime, starttime: DateTime, endtime: DateTime, sorting : String, ASKorDESK : String,  count : Int, page : Int): List<Course> – функция, для поиска, фильтрации и сортировки списка, которая получает список с заданными пользователем параметрами.
Функция с входными параметрами ID, NameGroup – название группы (курса), Costot – начальная цена за курс, Costdo – конечная цена за курс, Teacher – преподаватель, Type – тип курса, Branch – филиал, в котором занимается курс, Start – дата начала курса, End – дата конца курса, starttime – нижняя граница выборки данных по дате, endtime – верхняя граница выборки данных по дате, sorting – поле, по которому будет осуществляться сортировка, ASKofDESK - по возрастанию или по убыванию,  count – количество.  




