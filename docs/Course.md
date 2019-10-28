# Описание класса Course


## Атрибуты

- ID: Int
- NameGroup: String
- Cost: Double
- Teachers: List<[Worker](https://github.com/ "Объект класса Worker")>
- Type:  [Type](https://github.com/"Объект класса Type")
- Branch: [Branch](https://github.com/ "Объект класса Branch") 
- Start: DateTime
- End: DateTime
- EditDate: DateTime
- DelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- NameGroup: String - название курса(группы)
- Cost: Double - стоимость обучения на этом курсе
- Teachers: List<[Worker](https://github.com/ "Объект класса Worker")> - список преподавателей этого курса
- Type:  [Type](https://github.com/ "Объект класса Type") - тип курса
- Branch: [Branch](https://github.com/ "Объект класса Branch") - филиал, в котором этот курс обучается
- Start: DateTime - дата начала занятий этого курса
- End: DateTime - дата окончания занятий этого курса
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД