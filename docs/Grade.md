# Описание класса Grade

## Атрибуты

- ID: Int
- Date:	DateTime	 
- [Student](./Student.md "Класс Student")
- Grade: Int	
- [Timetable](./Timetable.md "Класс Timetable")
- Course: [Course](./Course.md "Класс Course")
- Theme:  [Theme](./Theme.md "Класс Theme")
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date:	DateTime	 - дата оценки
- Student:  [Student](./Student.md "Класс Student") - ученик
- Grade: Int - оценка	
- [Timetable](./Timetable.md "Класс Timetable") - конкретное занятие, элемент расписания
- Course: [Course](./Course.md "Класс Course") - курс
- Theme:  [Theme](./Theme.md "Класс Theme") - тема, за которую поставлена оценка
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД