# Описание класса Worker
    
Данный класс наследует все операции класса  [Person](./Person.md "Класс Person") . 


## Атрибуты

* ID: Int
* FIO: String
* Phone: String
* EditDate: DateTime
* DelDate: DateTime
* Position: String
* Type: Bolean
* Password: String
* Branch:  [Branch](./Branch.md "Класс Branch") 
* Rate: Double

## Описание атрибутов

* ID: Int - идентификатор в БД
* FIO: String - Фамилия Имя Отчество
* Phone: String - контактный телефон 
* EditDate: DateTime - дата редактирования данных в БД
* DelDate: DateTime - дата удаления данных из БД
* Position: String - должность 
* Type: Bolean - true – если преподаватель, false – если управляющая должность
* Password: String - пароль для авторизации в системе
* Branch: [Branch](./Branch.md "Класс Branch") - филиал, в котором работник работает на постоянной основе, если работник выполняет свои обязанности в нескольких филиалах, то это поле остается пустым
* Rate: Double - ставка
