# courses-joker

You need rename file .env.rename to .env & create command composer install 

## Задание 2 (Объектно-ориентированное):
###### Не использовать функции стандартной библиотеки.

###### Создайте класс с именем Logger, реализуйте все необходимые методы для работы с логированием данных:
* Обеспечьте возможность записи логов в файл
* Обеспечьте возможность задания уровня логов (TRACE, DEBUG, INFO, WARN, ERROR, FATAL)
* Файл с логами должен хранить следующую информацию (дата и время, сообщение, уровень), через разделитель  (по умолчанию точка с запятой).
* Обработать все возможные исключительные ситуации
* Продумать какие должны быть методы, параметры методов т.е. продумать структуру класса (Возможно это ряд классов… если это будет аргументированно)
* Реализовать pattern singleton для этого класса, - аргументировать, если считаете что singleton не допустим для этого задания - аргументировать
* (Задание повышенной сложности, не обязательно но будет плюсом). Реализовать механизм формата хранения логов. К примеру date, level, message. Если задан формат date: level, message В таком случае каждый лог должен быть в файле в таком же формате (2021-01-01 12:12:12: INFO, division by zero). Можно продумать свой вариант формата - здесь на свое усмотрение.

###### Остальные
* В заданиях из первого домашнего задания, где необходима обработка и проверка на корректность входных данных, обработать с помощью исключительных ситуаций.
* Создать класс “Фигура” унаследовать от него три класса “Прямоугольник”, “Треугольник” и “Круг”. Посчитать периметр и площадь фигуры. Объяснить на примере суть полиморфизма. Некорректные входные данные, обработать исключительными ситуациями. Нарисовать UML-диаграмму классов (интерфейсов).
* Проверить и поправить весь написанный код, как текущего задания, так и первого, таким образом чтобы он был написан в рамках стандартов кодирования PSR
* Написать свою простую реализацию MVC в связке с роутингом. Применить все знания ООП, SOLID, KISS, YAGNI, DRY
