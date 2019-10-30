# Описание класса Pay

## Атрибуты

- ID: Int
- Indicator: Boolean
- Contract:  [Contract](./Contract.md "Класс Contract")
- Worker: [Worker](./Worker.md "Класс Worker")
- Date: DateTime
- Payment: Double
- EditDate: DateTime
- DelDate: DateTime
- Type: Int
- Purpose: String


## Описание атрибутов

- ID: Int - идентификатор в БД
- Indicator: Boolean - указывает на тип договора ( true - оплата договора учеником, false - оплата зарплаты преподавателю
- Contract:  [Contract](./Contract.md "Класс Contract") - договор, по которому производится оплата
- Worker: [Worker](./Worker.md "Класс Worker") - работник, которому выплачивается зарплата
- Date: DateTime - дата произведения оплаты
- Payment: Double - количество внесенной оплаты
- EditDate: DateTime - дата редактирования данных в БД
- DelDate: DateTime - дата удаления данных из БД
- Type: Int - способ оплаты
- Purpose: String - предназначение оплаты