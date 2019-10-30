# Описание класса Timetable

## Атрибуты

- ID: Int
- StartLesson: DateTime
- EndLesson: DateTime
- Cabinet:  [Cabinet](./Cabinet.md "Класс Cabinet")
 -Course:  [Course](./Course.md "Класс Course")
- Teachers: Dictionary<[Worker](./Worker.md "Класс Worker"), boolean>
- Note: String
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- StartLesson: DateTime - время начала занятия
- EndLesson: DateTime - время окончания занятия
- Cabinet: [Cabinet](./Cabinet.md "Класс Cabinet") - кабинет, в котором проходит занятие
 -Course:  [Course](./Course.md "Класс Course") - курс
- Teachers: Dictionary<[Worker](./Worker.md "Класс Worker"), boolean> - список преподавателей, которые будут вести это занятие. Здесь же хранится информация о том, оплачено ли это занятие конкретному преподавателю или нет.
- Note: String - заметка, примечание
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД