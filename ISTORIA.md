(История операционных систем)

ЭВМ 1го поколения (ОС пока не существует)

Баллистические таблицы, расчёт 4 года.

Джон Мокли и Джон Эккерт – разработали первый компьютер ЭНИАК(электронный дифференциальный анализатор

ЭНИАК:

· Его скорость выполнения расчёта была 5 минут.

· Использовались лампы.

· Для перепрограммирования ЭНИАК использовали перемычки(провод переносился из одного отсека в другой).

· Данные хранились на перфокартах.

· Десятичная система

Архитектура фон Неймана:

· Переход к двоичной системе исчисления (сигнал есть - 1, нет - 0).

· Появление памяти взамен перфокарт.

· Память состоит из пронумерованных ячеек, и они имеют свой адрес.

· Программа - последовательность команд. Команды выполняются одна за другой.

· Последовательность может быть изменена.

ЭВМ 2го поколения (Появление первых ЯП)

В 50х годах появились транзисторы и имели плюсы по сравнению с лампами:

· Надёжность.

· Не выделяют тепло.

· Большая скорость переключения.

· Плотная компоновка деталей.

Минусы:

· Проблема соединения и ремонта.

· Дороговизна транзисторов.

Это привело к упрощению процесса разработки, появлению алгоритмических языков(COBOL,ALGOL), а также появление компиляторов.

ЭВМ 3-4го поколения

Проблемы ЭВМ 3го поколения:

· Вопросы размещения всех компонентов на полупроводнике(фотолитография).

· Как изолировать элементы друг от друга.

· Как соединить элементы между собой(напыление алюминия).

Итог привел к автоматизации производства и уменьшению цены.

ЭВМ 3го поколения(50-60г):

· Увеличение быстродействия.

· Ускорение ввода за счёт магнитных лент вместо перфокарт.

· Появление магнитного диска.

· Появление принципа мультипрограммирования.

· Появление принципа разделения времени.

· Появление IBM, UNIX.

ЭВМ 4го поколения(70-80г):

· Вытесняющая многозадачность.

· Появление виртуальной памяти.

· Появление концепции баз данных

· Размещение всех ИС на одном кристалле.

· Первый ПК ALTAIR 8800.

· Появление Apple.

UNIX

Развитие UNIX:

· Конец 60х – Разработка OS Multics.

· 1969 – Деннис Ритчи и Кен Томпсон – разработка UNIX ver 1.

· 1970 – Начало UNIX time.

· 1973 – UNIX ver 3.

· 1974 – Распространение в университетах.

· 1980 – Коммерческая версия от AT&T.

Идеология UNIX:

· Пишите программы, которые делают что-то одно, и делают хорошо.

· Программы должны работать вместе.

· Должны поддерживать текстовые потоки.

Linux

Создатель: Линус Торвальдс.

Функции ОС:

· Выполнение программы.

o Выделение процессорного времени

o Выделение памяти

o Обработка системных вызовов

· Управление памятью.

· Организация доступ к устройству посредством файловых систем.

· Стандартизированный доступ.

Совместимость ОС:

· Двоичная – приложение запускается без перекомпиляции.

· На уровне исходных кодов – необходима перекомпиляция.

Абстракция архитектуры:

1. Пользовательские программы

2. Ядро

3. Ассемблер

4. Микрокод

5. Аппаратное обеспечение

В UNIX выделены основные типы файлов:

· Символьные устройства.

· Блочные устройства.

· Каталоги.

· Ссылки.

· Именованные каналы.

· Сокеты

Задание 1:
```
Сокет – это файлы, обеспечивающие прямую связь между процессами, они могут передавать информацию между процессами, запущенными в разных средах или даже разных машинах. Это значит, что с помощью сокетов программы могут обмениваться данными даже по сети. По сути, сокет работает так же как туннели, но только в обе стороны.

Символьные устройства – вид файла устройства в UNIX/Linux-системах, обеспечивающий интерфейс к устройству, реальному или виртуальному, с возможностью посимвольного обмена информацией. В отличие от блочного устройства символьное устройство, как правило, не обладает возможностями произвольного доступа.

Именованные каналы – это особый тип файла (все файлы в Linux). Он существует как имя файла в файловой системе, но его поведение аналогично каналу без имени.
```
