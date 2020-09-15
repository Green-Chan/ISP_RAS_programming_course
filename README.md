# ISP RAS programming course

Данный репозиторий создан для сдачи домашних работ по курсу промышленного программирования на C/C++ Ильи Рудольфовича Дединского на базе ИСП РАН.

## Сборка и запуск тестов

Собрать *n*-тую домашнюю работу можно, выполнив make в папке, начинающейся с hw<*n*>. Запустить unit-тесты кдомашней работе, выполнив make test в соответствующей папке.

## Документация

Документация к *n*-той домашней работе, сгенерированная системой Doxygen, лежит в папке hw<*n*>&nbsp;<hw_name>/documentation.

Документации к содержимому папки unit_tests пока нет, потому что я предполагаю, что она может претерпевать крупные изменения в ближайшее время.

## Содержание

Возможно, часть домашних работ будет написана под Windows, а часть под Linux. Узнать это можно из описания соответствующей папки ниже.

> Note: В Windows в качестве аналога команды make я использую команду mingw32-make

### unit tests

Содержит файлы, используемые при написании unit-тестов к домашним работам. Пока что содержит версию только для Windows. Планируется по необходимости написать версию для Linux и по возможности версию, которая бы работала на обеих платформах.

### hw01 quadratic equation solver

Требовалось написать функцию, решающую квадратное уравнение. Несмотря на то, что сама функция (в файлах quadratic_equation_solver.cpp и quadratic_equation_solver.h) работает на обеих платформах, unit-тесты в том виде, в котором они написаны, можно запустить только на Windows и Makefile написан под под Windows.
