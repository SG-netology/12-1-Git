# 12-1-Git

Домашнее задание к занятию 12.1 «Базы данных» - Сергей Григорьев

Как вариант, данные хранятся в таблицах:

1 NSD (name, salary, date) - фамилия имя и отчество сотрудника, оклад, дата найма

2 Position - должность

3 Division – структурное подразделение

4 Type – тип подразделения

5 Project - проект

6 Region – край, область размещения филиала

7 City – город размещения филиала

8 Adress –улица, дом размещения филиала

NSD

Идентификатор, первичный ключ, serial

ФИО, varchar (150)

Оклад, decimal/numeric

Дата найма, date

Идентификатор должность (Position), внешний ключ, integer

Идентификатор структурное подразделение (Division), внешний ключ, integer

Идентификатор тип подразделения (Type), внешний ключ, integer

Идентификатор проект (Project), внешний ключ, integer

Идентификатор край, область размещения филиала (Region), внешний ключ, integer

Идентификатор город размещения филиала (City), внешний ключ, integer

Идентификатор улица, дом размещения филиала (Adress), внешний ключ, integer

Position

Идентификатор должность (Position), первичный ключ, serial

Должность, varchar (50)

Division

Идентификатор структурное подразделение (Division), первичный ключ, serial

Структурное подразделение, varchar (50)

Type

Идентификатор тип подразделения (Type), первичный ключ, serial

Тип подразделения, varchar (50)

Project

Идентификатор проект (Project), первичный ключ, serial

Проект, varchar (50)

Region

Идентификатор край, область размещения филиала (Region), первичный ключ, serial

Край, область размещения филиала, varchar (100)

City

Идентификатор город размещения филиала (City), первичный ключ, serial

Город размещения филиала, varchar (50)

Adress

Идентификатор улица, дом размещения филиала (Adress), первичный ключ, serial

Улица, дом размещения филиала, varchar (50)
