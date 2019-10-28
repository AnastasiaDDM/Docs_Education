# Описание класса Grade

## Атрибуты

- ID: Int
- Date:	DateTime	 
- [Student](./docs/Student.md "Класс Student")
- Grade: Int	
- [Timetable](./docs/Timetable.md "Класс Timetable")
- Course: [Course](./docs/Course.md "Класс Course")
- Theme:  [Theme](./docs/Theme.md "Класс Theme")
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date:	DateTime	 - дата оценки
- Student:  [Student](./docs/Student.md "Класс Student") - ученик
- Grade: Int - оценка	
- [Timetable](./docs/Timetable.md "Класс Timetable") - конкретное занятие, элемент расписания
- Course: [Course](./docs/Course.md "Класс Course") - курс
- Theme:  [Theme](./docs/Theme.md "Класс Theme") - тема, за которую поставлена оценка
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД