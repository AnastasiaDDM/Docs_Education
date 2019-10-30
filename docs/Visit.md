# Описание класса Visit

## Атрибуты

- ID: Int
- Date:	DateTime	 
- Student:  [Student](./Student.md "Класс Student")
- Visit: Bool	
- Timetable:  [Timetable](./Timetable.md "Класс Timetable")
- Course: [Course](./Course.md "Класс Course")
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date: DateTime - дата посещения	 
- Student:  [Student](./Student.md "Класс Student") - ученик
- Visit: Bool - true - ученик был на занятии, false	- отсутствие
- Timetable:  [Timetable](./Timetable.md "Класс Timetable") - конкретное занятие (элемент расписания)
- Course: [Course](./Course.md "Класс Course") - курс
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД
