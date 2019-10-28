# Описание класса Visit

## Атрибуты

- ID: Int
- Date:	DateTime	 
- Student:  [Student](https://github.com/"Объект класса Student") 
- Visit: Bool	
- Timetable:  [Timetable](https://github.com/"Объект класса Timetable") 
- Course: [Course](https://github.com/ "Объект классаCourse") 
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date: DateTime - дата посещения	 
- Student:  [Student](https://github.com/ "Объект класса Student") - ученик
- Visit: Bool - true - ученик был на занятии, false	- отсутствие
- Timetable:  [Timetable](https://github.com/ "Объект класса Timetable") - конкретное занятие (элемент расписания)
- Course: [Course](https://github.com/ "Объект классаCourse") - курс
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД
