# Описание класса Grade

## Атрибуты

- ID: Int
- Date:	DateTime	 
- Student:  [Student](https://github.com/"Объект классаStudent")
- Grade: Int	
- Timetable:  [Timetable](https://github.com/ "Объект класса Timetable")
- Course: [Course](https://github.com/ "Объект класса Course")
- Theme:  [Theme](https://github.com/ "Объект класса Theme")
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date:	DateTime	 - дата оценки
- Student:  [Student](https://github.com/ "Объект класса Student") - ученик
- Grade: Int - оценка	
- Timetable:  [Timetable](https://github.com/ "Объект класса Timetable") - конкретное занятие, элемент расписания
- Course: [Course](https://github.com/ "Объект класса Course") - курс
- Theme:  [Theme](https://github.com/ "Объект класса Theme") - тема, за которую поставлена оценка
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД