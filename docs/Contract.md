# Описание класса Contract


## Атрибуты


- ID: Int
- Date: DateTime
- Student: [Student](https://github.com/ "Объект класса Student")
- Branch:  [Branch](https://github.com/"Объект класса Branch")
- Manager: [Worker](https://github.com/"Объект класса Worker")
- Course:  [Course](https://github.com/ "Объект класса Course")
- Cost: Double
- PayofMonth: Double
- EditDate: DateTime
- DelDate: DateTime
- CancelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date: DateTime - дата заключения договора
- Student: Student [Student](https://github.com/ "Объект класса Student") - ученик, с которым заключен договор
- Branch:  [Branch](https://github.com/ "Объект класса Branch") - филиал, в котором договор заключен
- Manager: [Worker](https://github.com/ "Объект класса Worker") - менеджер, который заключил этот договор
- Course:  [Course](https://github.com/ "Объект класса Course") - курс, для которого заключен договор
- Cost: Double - стоимость за все обучение на этом курсе
- PayofMonth: Double - цена за месяц
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД
- CancelDate: DateTime - дата расторжения договора
