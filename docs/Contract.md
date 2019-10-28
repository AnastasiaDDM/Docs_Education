# Описание класса Contract


## Атрибуты


- ID: Int
- Date: DateTime
- Student: [Student](./docs/Student.md "Класс Student")
- Branch:  [Branch](./docs/Branch.md "Класс Branch")
- Manager: [Worker](./docs/Worker.md "Класс Worker")
- Course:  [Course](./docs/Course.md "Класс Course")
- Cost: Double
- PayofMonth: Double
- EditDate: DateTime
- DelDate: DateTime
- CancelDate: DateTime


## Описание атрибутов

- ID: Int - идентификатор в БД
- Date: DateTime - дата заключения договора
- Student: [Student](./docs/Student.md "Класс Student") - ученик, с которым заключен договор
- Branch:  [Branch](./docs/Branch.md "Класс Branch") - филиал, в котором договор заключен
- Manager: [Worker](./docs/Worker.md "Класс Worker") - менеджер, который заключил этот договор
- Course:  [Course](./docs/Course.md "Класс Course") - курс, для которого заключен договор
- Cost: Double - стоимость за все обучение на этом курсе
- PayofMonth: Double - цена за месяц
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД
- CancelDate: DateTime - дата расторжения договора
