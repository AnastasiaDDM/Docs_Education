# Описание класса Course


## Атрибуты

- ID: Int
- NameGroup: String
- Cost: Double
- Teachers: List<[Worker](./Worker.md "Класс Worker")>
- Type:  [Type](./Type.md "Класс Type")
- Branch: [Branch](./docs/Branch.md "Класс Branch")
- Start: DateTime
- End: DateTime
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- NameGroup: String - название курса(группы)
- Cost: Double - стоимость обучения на этом курсе
- Teachers: List<[Worker](./Worker.md "Класс Worker")> - список преподавателей этого курса
- Type:  [Type](./Type.md "Класс Type") - тип курса
- Branch: [Branch](./Branch.md "Класс Branch") - филиал, в котором этот курс обучается
- Start: DateTime - дата начала занятий этого курса
- End: DateTime - дата окончания занятий этого курса
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД