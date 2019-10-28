# Описание класса Timetable

## Атрибуты

- ID: Int
- StartLesson: DateTime
- EndLesson: DateTime
- Cabinet:  [Cabinet](https://github.com/ "Объект класса Cabinet")
 -Course:  [Course](https://github.com/ "Объект класса Course")
- Teachers: Dictionary<[Worker](https://github.com/ "Объект класса Worker"), boolean>
- Note: String
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- StartLesson: DateTime - время начала занятия
- EndLesson: DateTime - время окончания занятия
- Cabinet:  [Cabinet](https://github.com/ "Объект класса Cabinet") - кабинет, в котором проходит занятие
 -Course:  [Course](https://github.com/ "Объект класса Course") - курс
- Teachers: Dictionary<[Worker](https://github.com/ "Объект класса Worker"), boolean> - список преподавателей, которые будут вести это занятие. Здесь же хранится информация о том, оплачено ли это занятие конкретному преподавателю или нет.
- Note: String - заметка, примечание
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД